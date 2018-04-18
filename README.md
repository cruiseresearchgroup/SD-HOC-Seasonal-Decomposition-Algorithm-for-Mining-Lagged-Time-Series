> **If you use the resources (algorithm, code and dataset) presented in this repository, please cite our paper.**  
*The BibTeX entry is provided at the bottom of this page. 

# SD-HOC: Seasonal Decomposition Algorithm for Mining Lagged Time Series
Mining time series data is a difficult process due to the lag factor and different time of data arrival. In this paper, we present Seasonal Decomposition for Human Occupancy Counting (SD-HOC), a customised feature transformation decomposition, novel way to estimate the number of people within a closed space using only a single carbon dioxide sensor. SD-HOC integrates time lag and line of best fit model in the preprocessing algorithms. SD-HOC utilises seasonal-trend decomposition with moving average to transform the preprocessed data and for each trend, seasonal and irregular component, different regression algorithms are modelled to predict each respective human occupancy component value. Utilising M5 method linear regression for trend and irregular component and dynamic time warping for seasonal component, a set of the prediction value for each component was obtained. Zero pattern adjustment model is infused to increase the accuracy and finally, additive decomposition is used to reconstruct the prediction value. The accuracy results are compared with other data mining algorithms such as decision tree, multi-layer perceptron, Gaussian processes - radial basis function, support vector machine, random forest, naïve Bayes and support vector regression in two different locations that have different contexts.

This repository contains resources developed within the following paper:

    Arief-Ang I.B., Salim F.D., Hamilton M. (2018) SD-HOC: Seasonal Decomposition Algorithm for Mining Lagged Time Series.
    In: Boo Y., Stirling D., Chi L., Liu L., Ong KL., Williams G. (eds) Data Mining. AusDM 2017.
    Communications in Computer and Information Science, vol 845. Springer, Singapore
  
You can find the [paper](https://github.com/cruiseresearchgroup/DA-HOC-Semi-supervised-Domain-Adaptation-Prediction/blob/master/paper/BuildSys17_IrvanAriefAng.pdf) in this repository. 

Alternative link: https://link.springer.com/chapter/10.1007%2F978-981-13-0292-3_8

## Contents of the repository
This repository contains resources used and described in the paper.

The repository is structured as follows:

- `code/`: Code implementation and evaluation of SD-HOC.  
- `data/`: Preprocessed dataset used for this paper. 
- `paper/`: Formal description of the algorithm and evaluation result. 

## Possible Applications

## Citation
If you use the resources (code and dataset) presented in this repository, please cite (using the following BibTeX entry):
```
@book{ariefang2017sdhoc,
series = {Communications in Computer and Information Science},
issn = {1865-0929},
pages = {125--143},
volume = {845},
publisher = {Springer International Publishing},
booktitle = {Data Mining},
isbn = {978-981-13-0292-3},
year = {2018},
title = {SD-HOC: Seasonal Decomposition Algorithm for Mining Lagged Time Series},
author = {Arief-Ang, Irvan Bastian and Salim, Flora Dilys and Hamilton, Margaret},
}
```
