# Which interval do you want to use

​					Jump to:					[navigation](http://supermemopedia.com/wiki/Which_interval_do_you_want_to_use#mw-navigation), 					[search](http://supermemopedia.com/wiki/Which_interval_do_you_want_to_use#p-search) 			

## Contents

- [1 Executive summary](http://supermemopedia.com/wiki/Which_interval_do_you_want_to_use#Executive_summary)
- [2 Which interval do you want to use?](http://supermemopedia.com/wiki/Which_interval_do_you_want_to_use#Which_interval_do_you_want_to_use.3F)
- [3 Choices](http://supermemopedia.com/wiki/Which_interval_do_you_want_to_use#Choices)
- [4 Notes](http://supermemopedia.com/wiki/Which_interval_do_you_want_to_use#Notes)
- [5 Suppressing the interval question](http://supermemopedia.com/wiki/Which_interval_do_you_want_to_use#Suppressing_the_interval_question)
- 6 Why ever use minimum interval?
  - [6.1 When minimum is not minimum, and optimum is not optimum](http://supermemopedia.com/wiki/Which_interval_do_you_want_to_use#When_minimum_is_not_minimum.2C_and_optimum_is_not_optimum)
- [7 See also](http://supermemopedia.com/wiki/Which_interval_do_you_want_to_use#See_also)

# Executive summary

When SuperMemo asks you **Which interval do you want to use?** and you are not sure, press *Enter* and choose the default suggested by SuperMemo 17. Use other options if you are anxious about astronomically long intervals.

# Which interval do you want to use?

[SuperMemo 17](http://supermemopedia.com/wiki/SuperMemo_17) uses a new [algorithm](http://help.supermemo.org/wiki/SuperMemo_Algorithm). At the same time, it runs a parallel computations of the older  Algorithm SM-15. In certain circumstances, the intervals proposed by the two algorithms may differ. In addition, [SuperMemo](http://supermemopedia.com/wiki/SuperMemo) imposes constraints on interval change. For example, in the past,  SuperMemo always used to make sure intervals do not decrease. In new  SuperMemo, [DSR model](http://supermemopedia.com/wiki/DSR_model) suggests that in cramming, memories can weaken and intervals may decrease. You may wish to prevent interval decrease.

Most of interval differences have little to do with how memory  works. They are more about user strategies. For example, a user may wish to keep intervals short even if SuperMemo knows the [item](http://supermemopedia.com/wiki/Item) is remembered well.

To assist the user in making his or her choices, SuperMemo may display a question **Which interval do you want to use?**.

If you want to suppress this dialog and default to SuperMemo 17 algorithm use **Tools : Options : Learning : Algorithm SM-17 Alerts**. For example, put a large **Interval** value (e.g. 3000).

# Choices

Here are the interval options:

-  **SuperMemo 17 interval**: optimum interval proposed by  Algorithm SM-17 in agreement with the current status of memory for the  considered item (interval decrease may be prevented in shorter interval  ranges)
-  **SuperMemo 16 interval**: interval that SuperMemo 16 would have used. It might be very short if the user has previously manually  shortened the interval, even if the item is remembered very well
-  **DSR model interval**: optimum interval proposed by the [DSR model](http://supermemopedia.com/wiki/DSR_model) of memory in agreement with the current status of memory for the  considered item (this interval may be shorter than the used interval,  e.g. in cramming)
-  **Minimum interval**: minimum interval determined by the previously set interval incremented by one day (*old interval*+1). For example, if the previously set interval for the item was 3 years, minimum interval will be 3 years and 1 day
-  **Minimum non-regressive interval**: minimum interval determined by the used interval incremented by one day (*used interval*+1). For example, if the item has previously been reviewed a week ago, this interval will be 7+1=8 days

# Notes

-  Minimum non-regressive interval will often be longer than minimum  interval. For example, if SuperMemo planned a review in 7 days, but the  user came late and executed the review in 14 days, the minimum interval  will be 8 days, but minimum non-regressive interval will be 15 days
-  In SuperMemo 16, manual intervention leaves a permanent mark on the learning process. For example, if the user cuts the interval from 3  years to 3 months, the item will be subsequently reviewed as if its  optimum interval was 3 months indeed. This makes it possible to  intervene once, and never worry about the item again. In SuperMemo 17,  cutting the interval from 3 years to 3 months will work only for that  one interval. In the next review, SuperMemo 17 will always compute the  status of memory and will likely propose a long interval again (e.g. 4  years). This is the main source of differences between the two  algorithms
-  SuperMemo 17 may conclude that the next optimum interval is  actually shorter than the current interval. This may be the case for  very difficult, often badly formulated items. This can also happen in [cramming](http://supermemopedia.com/wiki/Cramming). Older SuperMemos would always employ non-regressive intervals. In the  past, the intervals would never get shorter. Using the interval dialog  you can choose between shorter interval (DSR Model) or anti-cramming  interval (SuperMemo 17). For example, the dialog may propose very long  intervals across the board except for the optimum interval determined by the DSR model. You can choose this shorter interval, however, you  should also have a look at the item. Perhaps it should be simplified.
-  minimum intervals are not too useful in regular work, however, may  come handy when resuming work after a longer break, or for beginners  (see: [Choice about what interval to use](http://supermemopedia.com/wiki/Choice_about_what_interval_to_use))

# Suppressing the interval question

If you want to always rely on the algorithm, ensure high speed of  learning and efficient memory stability calculations, you can suppress  the above dialog. This will take away some of your control over how  SuperMemo behaves, but it will also speed up the process of reducing  your repetition workload.

To suppress the dialog use **Tools : Options : Learning : Algorithm SM-17** and provide high values for **Difference** and/or **Interval**. For example, by setting **Interval=3650**, you will make sure the interval dialog will bother you only in cases  where SuperMemo 17 proposes intervals longer than 10 years (3650 days).

# Why ever use minimum interval?

Why would I ever want to use the minimum interval, which I understand as "no progress"? The whole point of SuperMemo is to use optimum  intervals, isn't it?

## When minimum is not minimum, and optimum is not optimum

SuperMemo 17 is true to your memory performance. On occasion, it can  tell you that you should shorten the next interval! This may happen if  the question is very difficult, and you are not really sure of the  answer. You may then happen to provide the right answer. This is even  more likely if you delay the review by a large margin. In lay language,  it is a situation where you "answer correctly even if you should rather  fail" (i.e. statistically, the correct answer is unlikely).

This is a real life example:

```
Which interval do you want to use?

SuperMemo 17 suggests: 10yr 2mth 30 days
SuperMemo 16 would use: 13yr 1mth 29 days
DSR model suggests: 3yr 1mth 2 days
Minimum interval: 9yr 1mth 14 days
Minimum non-regressive interval: 9yr 1mth 14 days
Help me understand the above!
Cancel
```

You will notice that **minimum interval** is actually longer than the **optimum interval** suggested by the DSR model. At the same time, SuperMemo 16 rigidly  enforces its two constraints: (1) intervals cannot get shorter, and (2)  U-factor cannot drop before a set minimum value.

Your decision here will depend on your learning criteria and the  importance of the item. Using DSR model interval will satisfy your  forgetting index goals, but will slow down learning. Using SuperMemo 16  will satisfy your speed of learning goals, which is ok as long as you  ruthlessly eliminate [leech](http://supermemopedia.com/wiki/Leech) items (i.e. items that are hard to remember due to bad formulation).  Choosing one of the minimum intervals falls in between in this  particular case, and would be a statement to this effect: "I do not  perform well with this item, but I refuse to make any step back".

# See also

-  [Choice about what interval to use](http://supermemopedia.com/wiki/Choice_about_what_interval_to_use)