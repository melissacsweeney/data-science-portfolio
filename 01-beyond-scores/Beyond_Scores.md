# Beyond Scores: Designing Health Data for Human Understanding

*Using NHANES data to explore patient-centered approaches to health measurement*

Over the last several decades, healthcare has increasingly shifted toward patient-centered care. We have seen growing emphasis on patient-reported outcomes, shared decision-making, quality of life, patient experience, self-management, and patient empowerment.

Yet many digital health products still organize themselves around scores, streaks, biomarkers, risk reduction, and engagement metrics. These measures are useful for clinicians and health systems. But they do not necessarily answer the questions ***users*** are asking.

A person opening a health app is often wondering:

- What patterns am I seeing?

- Is anything changing?

- Why am I having a good week versus a bad week?

- How do these different parts of my life fit together?

Most health companies are very aware that engagement is a challenge. Industry discussions often focus on retention, adherence, activation, churn, habit formation, and behavior change. The implicit question is often:

**How do we get people to engage more?**

An alternative question is:

**What would make the information more meaningful?**

An engagement-centered approach often emphasizes more reminders, more notifications, more streaks, and more gamification. A meaning-centered approach asks:

**How can we help users understand something valuable about themselves?**

This raises an interesting possibility:

**To what extent are engagement problems actually meaning problems?**

People return to things that are meaningful and help them make sense of something they care about. Nobody needs a reminder to reread a book that changed how they see the world. Nobody needs a push notification to remember a conversation that mattered.

Perhaps health data could function in a similar way. To explore this idea, I used NHANES (National Health and Nutrition Examination Survey) data to examine three different approaches to representing health information.

# 1. Heatmaps: What Patterns Matter?

Most nutrition feedback is score-based. A user might receive a dietary quality score of 62, then later see it increase to 67. That tells them they improved. It does not necessarily tell them how. To explore an alternative approach, I created dietary heatmaps for two individuals. The resulting visual resembles a behavioral fingerprint.

<img src="Fingerprints%20image.png" width="500">

The contrast between the two patterns is immediately visible. One participant's dietary pattern is characterized by vegetables, fruit, whole grains, and lean protein. The other pattern is characterized by processed snacks, processed foods, sugary drinks, and added sugar. Importantly, the value of the visualization is not simply that one pattern appears healthier than the other. The value is that users can see where the differences lie.

A score answers:

**Better or worse?**

A pattern answers:

***What's changing?***

Imagine watching this visualization evolve over several months. The user is no longer watching a number increase. They are watching their behavior change. This aligns with an important shift in nutrition science itself. Diet is increasingly understood as a dietary pattern, yet many user-facing tools still present nutrition as a series of disconnected metrics. A pattern-focused representation may be more intuitive, more meaningful, and ultimately more motivating than a single summary score.

# 2. Network Analysis: Where Does This Variable Sit in the System?

Many health analyses focus on prediction.

- Does caffeine predict depression?

- Does physical activity predict BMI?

- Does sleep predict inflammation?

These are valuable questions. But they are not the only questions. Another possibility is:

**Where does this variable live relative to the rest of the system?**

To illustrate this question, I created a simple network analysis including behavioral variables, wellbeing measures, and biological markers.

<img src="Network%20image.png" width="650">

Two patterns emerge:

First, depression appears to sit between wellbeing and biological measures, linking subjective experience and physiological indicators.

Second, caffeine illustrates an important point about variable selection. Caffeine is often omitted from analyses because it does not consistently emerge as a strong predictor of major outcomes such as depression. Yet when viewed through a network lens, caffeine appears closely connected to smoking behavior, highlighting relationships that might be overlooked when focusing only on direct associations with a single outcome.

This shifts the question from:

**Is caffeine statistically significant?**

to:

**How does caffeine relate to the rest of the system?**

This raises a broader question:

**Are there personally meaningful factors we overlook because they do not fit neatly into traditional outcome-focused analyses?**

Traditional statistical analyses help identify what tends to matter across a population on average. Individual users, however, are often asking a different question:

**What should I pay attention to in my own life?**

A user does not experience an average. A user experiences their own sleep, mood, energy, diet, and caffeine response. This is one reason there is growing interest in personalized medicine, N-of-1 studies, self-tracking, adaptive interventions, and individualized recommendations. Population-level findings remain essential. But users may also benefit from tools that help them discover patterns within their own systems.

# 3. Health Stages: Are We Measuring the Right Outcomes?

A third question concerns outcome selection itself. Many health analyses default to disease endpoints:

- Diabetes

- Heart disease

- Hypertension

These are important outcomes. But they are also relatively late-stage outcomes. If the goal is prevention, resilience, wellbeing, or behavior change, disease may not be the most informative place to look.

One way to think about this is through stages of health development.

| **Stage** | **Example Measures** |
| --- | --- |
| Wellbeing | Mood, energy, social connection |
| Behavior | Diet, sleep, physical activity |
| Biological / Risk | CRP, blood pressure, insulin sensitivity |
| Disease | Diabetes, cardiovascular disease |

Different measures capture different stages of the process. Many analyses focus on disease because disease is relatively easy to define.

- Diabetes: yes or no

- Heart disease: yes or no

- Hypertension: yes or no

But if we are interested in prevention, disease may be too far downstream. If we are interested in wellbeing, disease status may be too narrow. A person can have:

- No diagnosed disease

- Poor sleep

- Low energy

- Elevated inflammation

- Social isolation

- Reduced quality of life

Conversely, someone can have a diagnosis and still function and feel relatively well. This raises an important measurement question:

**What outcomes are we optimizing for, and are they appropriate to the stage of health users are trying to influence?**

# Conclusion

The three examples explored different questions. Taken together, they suggest a broader possibility. Many health systems become optimized around what is easiest to measure, validate, regulate, or report. Those goals are important. But they are not necessarily the same as helping a person ***find meaning in their metrics.***

If so, improving engagement may sometimes have less to do with reminders, notifications, and gamification, and more to do with *helping people see patterns, relationships, and progress in ways that feel personally relevant.*

Perhaps the future of digital health is not just better measurement. Perhaps it is better meaning-making.
