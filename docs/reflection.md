## Evaluation and Reflection 

**• How many of 20 did the model get right (by your judgment)?**

Model got 14 right out of 20


**• Did the model fail on the “tricky” examples? Why?**

Model only got 1 right prediction out of the 5 "tricky" ones.

"The special effects were amazing but everything else was terrible",

This is the only tricky review that model predicted right.


"Oh wow what a great movie... if you enjoy wasting 2 hours of your life".

 This was predicted as positive by the model possibly because it starts with a positive sentence but ends it negative making it overall negative. Model learned basic sentiments but not sarcasm


"Not bad but not great either, some parts were okay I guess",

This was predicted negative by the model however the review is neutral.


"I expected to hate it but it was surprisingly not terrible",

This was predicted as negative by the model but review is positive overall. It starts with a negative expectation, of hate, but ends positive. Model got confused by mixed signals


"Started amazing but ended so badly I wished I never watched it" 

This was predicted as positive by the model but is an overall negative review. Model predicted probably because it starts with positive words. 

**• Did the model handle out-of-domain examples? Why or why not?**

The model handled 3 out of 5 out-of-domain examples correctly. It is becaus the model learned sentiment patterns (positive & negative) from movie reviews which can be transferable to other domians but not always.

**• What does this tell you about your model’s generalization ability?**

The model generalizes and predicts well with straightforward reviews but struggles with reviews that have sarcasm and mixed signals. Suggesting the model learned basic sentiments but can not understand context given tbe sentence structure.

**• Would you trust this model in production based on this test?**

No, because it fails on sarcasm, mixed signals and out-of-domain examples. Sarcasm and mixed signal reviews are often part of production so the model can not be reliable.

