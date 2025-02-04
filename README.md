# EHRtemporalVariability-shiny

`EHRtemporalVariability-shiny` is an R Shiny app for delineating reference changes in Eletronic Health Records over time. This app uses and complements the R `EHRtemporalVariability` package (https://github.com/hms-dbmi/EHRtemporalVariability).

## What is this repository for?

The `EHRtemporalVariability-shiny` R Shiny app provides a graphical user interface to delineate reference changes over time in Electronic Health Records through the projection and visualization of differences among data temporal batches. This is done through the estimation of data statistical distributions over time and their projection in non-parametric statistical manifolds uncovering the patterns of the data latent temporal variability. Results can be explored through visual analytics formats such as Data Temporal heatmaps and Information Geometric Temporal (IGT) plots [1,2,3]. The supporting [EHRtemporalVariability R package](https://github.com/hms-dbmi/EHRtemporalVariability) can be used for more detailed and personalized analysis by users experienced in R coding.

Note that there are two shiny app R files:

* __EHRtemporalVariabilityShinyAppForLocalUse.R__: Besides the embedded demo and the loading of .RData files, it includes the loading and processing of csv files with raw data at individual level.
* __EHRtemporalVariabilityShinyAppForPublicUse.R__: It does not include the csv functionality.

## On line demo

An on line demo of the EHRtemporalVariability shiny app is available at http://ehrtemporalvariability.upv.es/

## Package Status

* __Version__: 1.0.1
* __Authors__: Carlos Sáez (UPV-HMS), Alba Gutiérrez-Sacristán (HMS), Isaac Kohane (HMS), Juan M García-Gómez (UPV), Paul Avillach (HMS)
* __Maintainer__: Carlos Saez (UPV-HMS)
 
Copyright: 2019 - Biomedical Data Science Lab, Universitat Politècnica de València, Spain (UPV) - Department of Biomedical Informatics, Harvard Medical School (HMS)

## Citation

A paper describing the EHRtemporalVariability package has been submitted. If you use EHRtemporalVariability, please cite:

Sáez C, Gutiérrez-Sacristán A, Kohane I, García-Gómez JM, Avillach P. EHRtemporalVariability: delineating unknown reference changes in Electronic Health Records over time. (Submitted)

The original methods and case studies using the approach are described here:

[1]: Sáez C, Rodrigues PP, Gama J, Robles M, García-Gómez JM. Probabilistic change detection and visualization methods for the assessment of temporal stability in biomedical data quality. Data Mining and Knowledge Discovery. 2015;29:950–75. https://doi.org/10.1007/s10618-014-0378-6

[2]: Sáez C, Zurriaga O, Pérez-Panadés J, Melchor I, Robles M, García-Gómez JM. Applying probabilistic temporal and multisite data quality control methods to a public health mortality registry in spain: A systematic approach to quality control of repositories. Journal of the American Medical Informatics Association. 2016;23:1085–95. https://doi.org/10.1093/jamia/ocw010

[3]: Sáez C, García-Gómez JM. Kinematics of Big Biomedical Data to characterize temporal variability and seasonality of data repositories: Functional Data Analysis of data temporal evolution over non-parametric statistical manifolds. International Journal of Medical Informatics. 2018;119:109–24. https://doi.org/10.1016/j.ijmedinf.2018.09.015

