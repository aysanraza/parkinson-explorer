# Parkinson Explorer
The multilayer Perceptron algorithm trained on Proteomics dataset of Parkinson disease for screening the new potential proteome.

## Problem Statement

Genome-wide association studies (GWAS) have provided a deeper understanding of the genetic basis of complex diseases, including Parkinson's disease (PD). However, there is still a need to identify new disease gene associations for PD. This research has the potential to generate new and improved hypotheses about the pathogenesis of PD.

## Introduction

This repository contains a parkinson-explorer that was trained on a dataset of 235 putative PD-associated proteins and 250 random proteins. The classifier achieved the following evaluation metrics:

* Precision: 95%
* Recall: 93%
* F1: 94%
* ROC: 98%

The classifier was also used to screen a neurodegenerative gene set consisting of 400 proteins to predict a new potential proteome consisting of 38 proteins. The new proteome plays a pivotal role in and around the synapse, performing molecular functions like RNA-binding, growth factors, and neuropeptides; playing or inserting an effect over major processes in and around mRNA processing, mRNA splicing, and neurogenesis.

## Installation

To install the parkinson-explorer, you will need to have Python 3 and the following Python packages:

* numpy
* pandas
* scikit-learn
* jupyter

You can install the dependencies using the following command:

```
pip install numpy pandas scikit-learn jupyter
```

Once the dependencies are installed, you can clone the repository using the following command:

```
git clone https://github.com/aysanraza/parkinson-explorer.git
```

## Usage

To use the carcinoma classifier, you will need to open the `parkinson-explorer.ipynb` file in Jupyter Notebook.

## Version History
* 0.1
  * Initial Release

## License
This project is licensed under the  MIT license - see the LICENSE.md file for details

## Authors
* Ahsan Raza
  * aysanraza@gmail.com
  * [Linkedin](https://www.linkedin.com/in/ahsan-raza-0510b1128/)

