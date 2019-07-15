# BENCHMARKING THE EFFECTIVENESS AND EFFICIENCY OF MACHINE LEARNING ALGORITHMS FOR RECORD LINKAGE

Record linkage which refers to the identification of the same entities across several databases in the absence of an unique identifier is a crucial step for data integration. In this research, we study the effectiveness and efficiency of different machine learning algorithms (SVM, Random Forest, and neural networks) to link databases in a controlled experiment. We control for % of heterogeneity in data and size of training dataset. We evaluate the algorithms based on (1) quality of linkages such as F1 score based on a one threshold model and (2) size of uncertain regions that need manual review based on a two threshold model. We find that random forests performed very well both in terms of traditional metrics like F1 score (99.2% - 95.9%) as well as manual review set size (7.1% - 21%) for error rates from 0% to 60%. Though in terms of F1 scores, the algorithms (Random Forests, SVMs and Neural Nets) fared fairly similar, random forests outperformed the next best model by 28% on average in terms of the percentage of pairs that need manual review.