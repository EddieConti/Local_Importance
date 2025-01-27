# Local_Importance

In this repository we provide the Experimental results concerning the paper "Generalization of Jaccard index for counterfactuals to estimate feature importance". In this paper we propose a novel local feature importance method that can be applied to any model. The general idea is to obtain two sets of positive and negative counterfactuals, estimate their underlying distributions with Kernel Density Estimations (KDE), and rank the features where positive and negative counterfactuals differ the most.
We demonstrate the effectiveness of our method by illustrating and comparing the results with traditional and well-established local feature importance scores. Furthermore, we incorporate the faithfulness metric as an additional point of comparison, complementing our analysis and providing a more comprehensive evaluation of the differences between metrics.
In the dataset folder there are the 4 dataset we used: Adult Income, Diabetes, Healt Disease and Student Depression.
In the Results folder the comparison between the various feature importance scores for a specific instance of the test dataset
The notebook provides the local importance scores, the analysis and comparison of the different metrics, the generation of the tables and plots and the computation of feature agreement score and comprehensiveness.
