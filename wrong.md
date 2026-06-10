---
title: 'How Not to be Wrong About AI'
teaching: 10
exercises: 10
---

:::::::::::::::::::::::::::::::::::::: questions 

- TODO

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- TODO

::::::::::::::::::::::::::::::::::::::::::::::::

<!-- add links please --->

In 2023, GitHub announced their tools made developers 55% faster. 
That number appeared in every executive presentation for a year.
This episode teaches you how to tell if you should believe it or not.

## Why Productivity is Hard to Define

Manufacturing productivity means widgets per hour: both terms are measurable.
But software output is not homogeneous: a ten-line bugfix may be worth more than a thousand-line feature.
An entire book [Sadowski2019] basically says “this is really hard” over and over again…

Much of software work is invisible: reading, reviewing, helping colleagues.
A field study found developers only spend 25% of their day actually writing code [Meyer2017].

**Construct validity**: does the measurement actually capture the concept?
Lines of code written per day has low construct validity — you can write more lines by making code worse.

Here are some common mistakes made by people trying to measure productivity in software development:

* Counting lines of code generated: measures verbosity, not value.
* Timing artificial tasks: a 90-minute greenfield task does not predict real work.
* Measuring only the easy half: AI makes code generation faster, but doesn’t count review time, debugging confidently wrong suggestions, and security vulnerabilities.
* Before/after with no control group: you cannot separate the AI effect from anything else that changed.
* Asking developers if they feel more productive: feeling productive is not the same as being productive, and the novelty effect inflates self-reports for weeks.
* Comparing people who volunteer to try a new tool or technique to those who do not: early adopters are usually already higher performers.

## Evaluating Claims
Claims can be evaluated from several angles:

* **Conclusion validity**: Was the sample large enough? Are effect sizes reported?
* **Internal validity**: Was there a control group? Was assignment random? Could novelty or learning effects explain the result?
* **Construct validity**: Does the measurement actually capture the claim?
* **External validity**: Who are the subjects, and are they representative of the population the conclusions address?

This is Research Methods 101… but most organizations (even ones staffed by scientists) don’t have the resources or skills to look at themselves this carefully.

## Minimum Viable Rigour
**Formative evaluation** means studying something in order to improve it.
This can be done effectively with small samples, rapid iteration, and a qualitative focus; “what is wrong?” not “how often?”

**Summative evaluation** is the assessment of whether something works in general.
It requires more participants, controlled conditions, and quantitative metrics.

You may have identified parallels to the distinction between formative and summative evaluation for assessing learning.
User experience groups in industry use the term “guerilla research” for formative evaluation.
A think-aloud session with five participants is typically enough to identify most problems in a specific workflow for a specific user group [Nielsen1993].

## In the Classroom
Instructors have the opportunity to run a formative evaluation session each time they teach with AI coding tools.
For example, you could ask learners to verbalize their thoughts as they work: _"say out loud whatever you are thinking"_.
Do this on a concrete task, not open exploration <!-- explain why --->
For example, _"Given this pull request, use the AI assistant to write a one-paragraph summary of the changes"_.
Then:

* Observe where participants hesitate, backtrack, or state expectations that turn out to be wrong.
* Do not help when they get stuck: their reasoning process is what you want to observe.
* Summarize observations at the end and have other learners compare with their own experience.

::::::::::::::::::::::::::::::::::::::::::::::::: discussion

### Practicing This Exercise

Work in groups of 3.
One person builds a script to find duplicate files (i.e., files with identical content but different names) in or below a directory (searching recursively) - the motivation is that it will be used to detect redundant copies of datasets or photographs.
They use an AI coding assistant while thinking aloud for at most 5 minutes. The others watch and take notes. 

At the end, compare the observers’ notes to each other and to the subject’s recollection of what they thought they were doing.

What would you tell the next person to do (in particular, to do differently) based on what you observed?

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: keypoints 

- TODO

::::::::::::::::::::::::::::::::::::::::::::::::

