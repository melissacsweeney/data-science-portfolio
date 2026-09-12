Is the Evidence Strong Enough to Build the Feature?

A digital health app for cardiology patients is considering an adherence-support feature built around medication reminders and refill nudges. The idea comes from an existing observation that people who use statins appear to have better health outcomes.

The product question is:

Among people who are supposed to be taking statins, would improving their adherence improve outcomes enough to justify building the feature?

Using NHANES data, this project examines whether the observed difference in self-reported health between current statin users and non-users remains after making the groups more comparable on measured characteristics.

Read the analysis

→ Read Is the Evidence Strong Enough to Build the Feature

Technical work

The analysis:

Compares the raw proportion of statin users and non-users reporting good health.

Uses propensity score matching based on age, sex, income, physical activity, smoking history, and healthcare use.

Checks covariate balance before and after matching.

Uses McNemar's exact test for the paired matched outcome comparison.

Interprets the findings in terms of causal reasoning and the product decision.

Methods: propensity score matching · covariate balance · McNemar's exact test · observational data · causal reasoning · experimentation

Key finding

The raw comparison showed that 62.1% of statin users reported good health compared with 67.2% of non-users, a difference of about 5.1 percentage points.

After matching, the difference shrank to about 3.9 percentage points, and the matched comparison was not statistically significant (McNemar's exact test, p = 0.0921).

The result does not establish that statin use has no effect. Rather, the observational data do not provide strong enough evidence to justify building an adherence-support feature on the basis of this association alone.

Product implication

The analysis points to a question beyond the statistical comparison: why are patients missing their medication?

If forgetting is the main barrier, reminders or refill nudges could be tested in a small A/B experiment. If the barrier is instead cost, side effects, or concerns about the medication, a reminder feature may be solving the wrong problem.
