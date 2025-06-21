[Home](../README.md) > [Catalogue](../Patterns_catalogue.md) > [Categories](categories/categories.md) > [Grading](categories/Grading.md) >  Whodunnit? - Using metrics in a fair way

#  Whodunnit? - Using metrics in a fair way

## Category

[Grading](categories/Grading.md)

## Context

A professional tool stack is common to use in software engineering projects. Therefore it should come as no surprise that students are required to use a tool stack in their projects and steer their project accordingly. Some of the data provided by the tool stack could also be used to get an impression of the performance of the individual students. Some examples are: hours spent on tasks, lines of code committed, number of pull requests, number of edits to documents and number of review comments. Depending on the tool stack being used, you can even dive deeper and use for instance blame of code which made it to the main branch, track when and for how long the students worked (date/time), or click through to the underlying work and see for yourself if the work was substantively correct. With so many potential data available it would be easy to misinterpret them or to simply drown in numbers.

## Problem

How do you use metrics from a tool stack in a good way?

## Forces

 - **Doubts about the definitions.** While many tool stacks provide nice graphs and data, most of the times it is far from 100% clear how the underlying data are compiled. What exactly is counted in the number of lines of code? All code on the development branch as well as on the main branch? In- or excluding comments? Once you start doubting this, you could feel tempted to stop using (other) information from the tool stack as well.
 - **Downplaying the value of the metrics.** It is tempting to see the metrics as a single point of truth concerning the contributions of the individuals in the project team. But the explanations on the metrics above show that is dangerous to take these metrics literally. Although their numbers are fairly different, two people could have done roughly the same amount of work. But, having said that, it would also be unfair too to say that these metrics are therefore completely useless.

## Solution

The solution is a process again:
 - **Cost before benefit.** If you want to work with metrics, you need to delve into the possibilities offered by the specific tool stack and discuss with your colleagues what should be the most useful metrics. The tool stacks are not designed for grading information, so you need to figure out which possibilities there are. Sometimes you even need to write a plugin to derive the data from the stack.
 - **Train students how to use the tool stack properly.** The success of their project depends partly on the use of the tool stack. This means that just telling how to use is is not enough. Check on them using it correctly and let them adapt if necessary.
 - **Calculate the averages for every metric.** This gives you a hint of the project team’s productivity as a whole.
 - **Look for outliers.** Be ’suspicious’ of the students who score very high or low towards an average. It goes without saying that the lowest scorers might be doing too little. On the other hand the highest scorers might be frequent-committers or the students who correct language errors one by one; their high score certainly does not necessarily mean they are the most industrious.
 - **Some rules of thumb you could use when interpreting
the numbers:**
  – Students who score more than approximately 20 percent above or below average have your special interest. 20 percent is of course an arbitrarily chosen border, 15 percent could work as well. The objective is to help you to differentiate between ’the good majority’ and outliers.
  – For hours spent on tasks: 50-60 percent of the available time is directly spent on tasks concerning the product-tobe. We expect students to work 40 hours per week on their project, so approximately 20-24 hours should be traceable in the tool stack.

## Consequences

 - (+) Working with a tool stack gives you insights in the progress of the team you guide, even if you are not there in person.
 - (-) If students become too focused on becoming number one
in the charts they put the cart before the horse. Then Goodhart’s becomes true: "When a measure becomes a target, it
ceases to be a good measure" [3].

## Related Patterns

|Pattern  | Relation |
|--|--|
|[2+2 makes four eyes- Grading individuals is teamwork](2_2_makes_four_eyes.md)|uses in solution|

## Example(s) / Known Use(s)

## Sources

[[JAC'24]](../References.md)

