# Quantum Artificial Neuron

This repositories contains the source code for the implementation of the quantum artificial neuron model suggested by [Tacchino et al.](https://www.nature.com/articles/s41534-019-0140-4) and [Mangini et al.](https://iopscience.iop.org/article/10.1088/2632-2153/abaf98/meta). The models are:
* Brute force (Tacchino et al.);
* Hypergraph State Generation Subroutine, HSGS (Tacchino et al.);
* Continuous valued input data neuron (Mangini et al.).

These models are to be combined with a classic algorithm to handle weights and applied on known datasets in order to analyse the results. Classic models will also be implemented in order to compare the outcome. 

The datasets chosen were both from [UCI Datasets](https://archive.ics.uci.edu/ml/datasets.php):
* [Breast Tissue Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Tissue)
* [Cesarian Section Classification Dataset](https://archive.ics.uci.edu/ml/datasets/Caesarian+Section+Classification+Dataset)

Metrics that are to be analyzed:
* [RoC Curve] (https://en.wikipedia.org/wiki/Receiver_operating_characteristic);
* [McNemar's test](https://en.wikipedia.org/wiki/McNemar%27s_test);
* Accuracy;

This code will be used as tool for a Bachelor Thesis for CIn/UFPE by student Eduardo Barreto Brito, with Felipe Maciano de Paula Neto as professor.
