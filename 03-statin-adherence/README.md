# Is the Evidence Strong Enough to Build the Feature?

*A decision-focused analysis of observational evidence for a medication-adherence feature*

A digital health app for cardiology patients is considering an adherence-support feature built around medication reminders and refill nudges. The idea comes from an existing observation that people who use statins appear to have better health outcomes.

The product question is:

**Among people who are supposed to be taking statins, would improving their adherence improve outcomes enough to justify building the feature?**

Using NHANES data, I compared current statin users with non-users. I first examined the raw difference in self-reported general health, then used propensity score matching to make the groups more comparable on measured characteristics.

## Read the analysis

**[→ View the analysis notebook](./Is_the_Evidence_Strong_Enough.ipynb)**

## What the analysis found

The matched comparison showed a **statistically significant but small difference** in reported good health, approximately 4%.

That result is not strong enough on its own to justify building a reminder feature. The analysis is observational, matching cannot account for unmeasured differences between groups, and the dataset does not directly measure medication adherence.

## What I would do next

**Study the relationship more directly.** A cohort design following patients from statin initiation would establish temporal sequence and allow adherence to be studied alongside subsequent outcomes.

**Check the feature design.** Before assuming reminders are the solution, identify why patients are missing their medication. Forgetting, cost, side effects, and concerns about medication require different interventions.

**Then run a small experiment.** If forgetting is a meaningful barrier, an A/B test of reminders or refill nudges would be a logical next step. If another barrier is more important, the experiment should target that instead.

## Methods

Propensity score matching · logistic regression · nearest-neighbor matching · statistical testing · observational data · causal reasoning · experimentation
