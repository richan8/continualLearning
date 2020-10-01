# continualLearning
Continual Learning for robotic perceptron
The .ipynb notebook may be previewed here, or can be run on kaggle.

## Summary of Results

It is evident from the graph that as the number of tasks increases, there is a significant relative increase in the accuracy of the model that applies the Continous Learning technique of Elastic Weights Consolidation, as compared to the model that that does not employ any Continous Learning Techniques. As discussed earlier, many other techniques can also be applied to this but some (for example: Naive method, Shuffled Rehersal techniques etc.) are not the best options for this since they result in an ever increasing memory requirement as the number of tasks increases which would bot not be an ideal solution for most cases of robotic perception.

The strength of using EWC is that the memory requirement increments are negligible compared to these techniques. In general, a large number of real life applications in machine learning involve data is dynamic, streamed, or occurs in batches such that the model needs to retrain at constant intervals. it is noted and observed that Continual Learning techniques is the solution to these machine learning problems.
