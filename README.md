# Causal Discovery

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

-----

## Table of contents

* [Research papers](#Research-papers)
  * [Causal graph](#Causal-graph)
  * [Cause-effect pairs](#Cause-effect-pairs)
  * [arXiv](#arXiv)

* [Datasets](#Datasets)

* [References](#References)

* [Contact](#Contact)

* [License](#License)

-----

## Research papers

### Causal graph

#### Constraint-based methods

|paper|confounder|continuous|discrete|
|---|---|---|---|
|(**FCI**) [*Causation, prediction, and search*](https://mitpress.mit.edu/books/causation-prediction-and-search-second-edition)<br>MIT press 2000|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|(**PC**) [An algorithm for fast recovery of sparse causal graphs](https://pdfs.semanticscholar.org/30d4/d4c7505008ea7362ec369311445f4bc8d27a.pdf) <br> *Social science computer review* 2000||:heavy_check_mark:|:heavy_check_mark:|
|(**SGS**) [Causality from probability](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.650.9968&rep=rep1&type=pdf) <br> *Conference Proceedings: Advanced Computing for the Social Sciences* 1990||:heavy_check_mark:|:heavy_check_mark:|

#### Methods based on functional causal model

|paper|confounder|continuous|discrete|
|---|---|---|---|
|(**PairwiseLiNGAM**) [Pairwise likelihood ratios for estimation of non-Gaussian structural equation models](http://www.jmlr.org/papers/volume14/hyvarinen13a/hyvarinen13a.pdf)<br>*Journal of machine learning research* (**JMLR**) 2011||:heavy_check_mark:||
|(**DirectLiNGAM**) [DirectLiNGAM: A direct method for learning a linear non-Gaussian structural equation model](http://www.jmlr.org/papers/volume12/shimizu11a/shimizu11a.pdf) <br> *Journal of machine learning research* (**JMLR**) 2011||:heavy_check_mark:||
|(**LiNGAM**) [A linear non-Gaussian acyclic model for causal discovery](http://www.jmlr.org/papers/volume7/shimizu06a/shimizu06a.pdf) <br> *Journal of machine learning research* (**JMLR**) 2006||:heavy_check_mark:||

#### Score-based methods

|paper|confounder|continuous|discrete|
|---|---|---|---|
|(**fGES**) [A million variables and more: the Fast Greedy Equivalence Search algorithm for learning high-dimensional graphical causal models, with an application to functional magnetic resonance images](https://link.springer.com/article/10.1007/s41060-016-0032-z)<br>*International journal of data science and analytics* 2017||:heavy_check_mark:||
|(**GES**) [Optimal Structure Identification With Greedy Search](http://www.jmlr.org/papers/v3/chickering02b.html) <br> *Journal of machine learning research* (**JMLR**) 2002||:heavy_check_mark:||

#### Hybrid methods

|paper|confounder|continuous|discrete|
|---|---|---|---|
|(**GFCI**) [A hybrid causal search algorithm for latent variable models](http://proceedings.mlr.press/v52/ogarrio16.pdf)<br>*Conference on Probabilistic Graphical Models* (**PGM**) 2016||:heavy_check_mark:||
|(**GES**) [Optimal Structure Identification With Greedy Search](http://www.jmlr.org/papers/v3/chickering02b.html) <br> *Journal of machine learning research* (**JMLR**) 2002||:heavy_check_mark:||

### Cause-effect pairs

#### Methods based on functional causal model

|paper|confounder|continuous|discrete|
|---|---|---|---|
|(**IGCI**) [Inferring deterministic causal relations](https://arxiv.org/abs/1203.3475)<br>*Conference on uncertainty in artificial intelligence* (**UAI**) 2010||:heavy_check_mark:||
|(**PNL**) [On the identifiability of the post-nonlinear causal model](https://dl.acm.org/citation.cfm?id=1795190) <br> *Conference on uncertainty in artificial intelligence* (**UAI**) 2009||:heavy_check_mark:||
|(**ANM**) [Nonlinear causal discovery with additive noise models](http://papers.nips.cc/paper/3548-nonlinear-causal-discovery-with-additive-noise-models.pdf) <br> *Advances in neural information processing systems* (**NIPS**) 2009||:heavy_check_mark:|:heavy_check_mark:|

#### Methods based on complexity measure

|paper|confounder|continuous|discrete|
|---|---|---|---|
|(**CURE**) [Inference of cause and effect with unsupervised inverse regression](http://proceedings.mlr.press/v38/sgouritsa15.pdf)<br>*Artificial intelligence and statistics* (**AISTATS**) 2015||:heavy_check_mark:||
|(**GPI**) [Probabilistic latent variable models for distinguishing between cause and effect](http://papers.nips.cc/paper/4173-probabilistic-latent-variable-models-for-distinguishing-between-cause-and-effect) <br> *Advances in neural information processing systems* (**NIPS**) 2010||:heavy_check_mark:||

### arXiv

TBD

-----

## Datasets

|     Dataset    |        #Sample |       #Feature      | #Class |   Subdomain  | Reference |
|:--------------:|:-------:|:-------------------:|:------:|:------------:|:--------:|
| [Office+Caltech](#Office+Caltech) |    2533  | SURF: 800, DeCAF: 4096 |   10   |  A, W, D, C  |   [[1]](#1)       |
|     [VOC2007](#vlcs)    |          3376  |      DeCAF: 4096     |    5   |       V      |    [[2]](#2)      |
|     [LabelMe](#vlcs)    |          2656  |      DeCAF: 4096     |    5   |       L      |    [[3]](#3)      |
|   [Caltech101](#vlcs)   |          1415  |      DeCAF: 4096     |    5   |       C      |    [[4]](#4)      |
|      [SUN09](#vlcs)     |          3282  |      DeCAF: 4096     |    5   |       S      |    [[5]](#5)      |

### Office+Caltech

#### Introduction

This dataset is constructed by collecting common classes in two datasets: Office-31 (which contains A, W and D) and Caltech-256 (which is C).  
Four domains: A(Amazon, 958 instances), W(Webcam, 295 instances), D(DSLR, 157 instances), and C(Caltech, 1123 instances).  
Ten common classes: back pack, bike, calculator, headphones, keyboard, laptop_computer, monitor, mouse, mug, and projector.

#### Download

Download Office+Caltech original images [[Google Drive](https://drive.google.com/file/d/14OIlzWFmi5455AjeBZLak2Ku-cFUrfEo/view?usp=sharing)]  
Download Office+Caltech SURF dataset [[Google Drive](https://drive.google.com/file/d/1TKot-lmTy5h797YaAeydkOD6kWqii5fa/view?usp=sharing)]  
Download Office+Caltech DeCAF dataset [[Google Drive](https://drive.google.com/file/d/1mgEyml0ZoZjUlUQfWNfr-Srxmlot3yq6/view?usp=sharing)]

### VLCS

#### Introduction

Four domains: V(VOC2007), L(LabelMe), C(Caltech), and S(SUN09).  
Five common classes: bird, car, chair, dog, and person. 

#### Download

Download the VLCS DeCAF dataset [[Google Drive](https://drive.google.com/drive/folders/1yvIpp0kg8e-GHESF6jJjCO4M7mjOJHLS?usp=sharing)]

-----

## References

TBD

-----

## Contact

* **Shoubo Hu** - shoubo [dot] sub [at] gmail [dot] com

See also the list of [contributors](https://github.com/amber0309/Domain-generalization/graphs/contributors) who participated in this project.

-----

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
