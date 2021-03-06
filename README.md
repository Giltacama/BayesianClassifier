## CABBAGE
#### Classification Algorithm Based on a BAyesian method for GEnomics

An application developed in Perl that allows the classification feature extraction and bootstrapping of genomic sequences, in order to improve data visualization and usefulness for genomic applications

The application is built from three standalone modules:
### Bayesian Classifier, Feature Extraction and Bootstrapping

* The Bayesian Classifier, this module uses a Naive Bayes Classifier technique wich is based on the so-called Bayesian theorem and is particularly suited when the dimensionality of the inputs is high. Despite its simplicity, Naive Bayes can often outperform more sophisticated classification methods. The module classifies genomic sequences into predetermined classes using a training genome matrix of known parameters (e.g. disease, host age, host sex, geographic location, drug resistance etc.)

* The Feature Extraction, the classification has the problem of high dimensionality of feature space due to the extensive information from genomic data. This high dimensionality of feature space is solved by feature selection and feature extraction methods and improves the performance of categorization.The feature selection and feature extraction techniques remove the irrelevant features from the test and reduce the dimensionality of feature space. The module accomplishes this task by the use of a statistics test (Chi squared) extracting the genes or genomic regions associated to the predefined class.

* The Bootstrapping, the bootstrap is a tool for making statistical inferences when standard parametric assumptions are questionable. For the particular case of genomics data size, can be an issue such problems can be biased be the use on this module wich, generates random samples from a population with a certain distribution this way unevenness of classes can be overcome.
