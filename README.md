# ENDG511
This repository will contain the source code for the lab assignments in the course. 

# Summary
From this lab report, it was observed that a very high learning rate can yeild
poor performances much like a very small learning rate can yeild poor performances.
It is important to **find the optimal learning rate** that yeilds the best performances
for a given number of epochs for training. 

Furthermore, *decreasing the number of neurons* in the Dense layer by a factor of
16 substantially *reduced the inference time* of the model by a factor of 112000.
Furthermore, it *decreased the model's accuracy by ~8%*, 
*decreased the model parameters by factor of 15*, and 
*decreased the model size by a factor of 5.* 

On the other hand, *increasing the number of neurons* in the Dense layer by a
factor of 16, substantially *reduced the inference time* of the model by a factor
of 62000, *decreased the accuracy by 0.1%, and increased the model's size by a factor of 45.* 

Incorporating CNN layers onto the FC neural network reduced the number of parameters
of the model by ~30,000 - 40,000. Furthermore, CNN incorporation yeilds a model
that is ~77850x faster and ~0.6x smaller, and 1-2% higher in accuracy.