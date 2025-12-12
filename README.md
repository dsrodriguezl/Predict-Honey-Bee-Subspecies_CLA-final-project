# ML classification of honey bees based on their cuticular hydrocarbon composition

## Overview
The cuticular hydrocarbons (CHCs) are complex mixtures of hydrocarbon that cover the outer surface of the body of insects. The composition of these mixtures directly depends on an insect's genetics. In my PhD, I showed that the CHC composition of honey bees (*Apis mellifera*) differs between subspecies. The corresponding research was published in BMC Ecology and Evolution (2024) under the title "Deciphering the variation in cuticular hydrocarbon profiles of six European honey bee subspecies" (DOI: 10.1186/s12862-024-02325-z).

The goal of this project was to develop a machine learning (ML) classifier for honey bee subspecies based on the cuticular hydrocarbon composition of the bees.
This could help monitoring the distribution of honey bee subspecies. 
It would provide another alternative to assess the subspecies of honey bees, in case the access to molecular methods is restricted.

I developed and compared three different ML classification methods (Support Vector Machine, Random Forest, and Multi-Layer Perceptron), using the CHC composition data from my own research. The data is publicly available as a persistent Figshare repository (https://doi.org/10.6084/m9.figshare.26831008.v1).

The development and comparison of the performance of the classifiers are documented in the classifier_development Jupyter Notebook.
