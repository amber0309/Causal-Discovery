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

<table>
  <tr>
    <td colspan="3"><b>With confounders</b></td>
  </tr>
  <tr>
    <td>(<b>FCI</b>)<a href="https://mitpress.mit.edu/books/causation-prediction-and-search-second-edition"> <i>Causation, prediction, and search</i></a></td>
    <td>Spirtes, Peter and Glymour, Clark N and Scheines, Richard and Heckerman, David and Meek, Christopher and Cooper, Gregory and Richardson, Thomas</td>
    <td>MIT press 2000</td>
  </tr>
</table>

<table>
  <tr>
    <td colspan="3"><b>Without confounder</b></td>
  </tr>
  <tr>
    <td>(<b>PC</b>)<a href="https://pdfs.semanticscholar.org/30d4/d4c7505008ea7362ec369311445f4bc8d27a.pdf"> An algorithm for fast recovery of sparse causal graphs</a></td>
    <td>Spirtes, Peter, and Clark Glymour</td>
    <td><i>Social science computer review</i> 2000</td>
  </tr>
  <tr>
    <td>(<b>SGS</b>)<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.650.9968&rep=rep1&type=pdf"> Causality from probability</a></td>
    <td>Spirtes, Peter, Clark N. Glymour, and Richard Scheines</td>
    <td><i>Conference Proceedings: Advanced Computing for the Social Sciences</i> 1990</td>
  </tr>
</table>

#### Methods based on functional causal model

**Without confouder**

|Title|Authors|Venue|
|---|---|---|
|(**PairwiseLiNGAM**) [Pairwise likelihood ratios for estimation of non-Gaussian structural equation models](http://www.jmlr.org/papers/volume14/hyvarinen13a/hyvarinen13a.pdf)|Hyvärinen, Aapo, and Stephen M. Smith|*Journal of machine learning research* (**JMLR**) 2011|
|(**DirectLiNGAM**) [DirectLiNGAM: A direct method for learning a linear non-Gaussian structural equation model](http://www.jmlr.org/papers/volume12/shimizu11a/shimizu11a.pdf)|Shimizu, Shohei, Takanori Inazumi, Yasuhiro Sogawa, Aapo Hyvärinen, Yoshinobu Kawahara, Takashi Washio, Patrik O. Hoyer, and Kenneth Bollen|*Journal of machine learning research* (**JMLR**) 2011|
|(**LiNGAM**) [A linear non-Gaussian acyclic model for causal discovery](http://www.jmlr.org/papers/volume7/shimizu06a/shimizu06a.pdf)|Shimizu, Shohei, Patrik O. Hoyer, Aapo Hyvärinen, and Antti Kerminen|*Journal of machine learning research* (**JMLR**) 2006|

#### Score-based methods

|Title|Authors|Venue|
|---|---|---|
|(**fGES**) [A million variables and more: the Fast Greedy Equivalence Search algorithm for learning high-dimensional graphical causal models, with an application to functional magnetic resonance images](https://link.springer.com/article/10.1007/s41060-016-0032-z)|Ramsey, Joseph, Madelyn Glymour, Ruben Sanchez-Romero, and Clark Glymour|*International journal of data science and analytics* 2017|
|(**GES**) [Optimal Structure Identification With Greedy Search](http://www.jmlr.org/papers/v3/chickering02b.html)|Chickering, David Maxwell|*Journal of machine learning research* (**JMLR**) 2002|

#### Hybrid methods

|Title|Authors|Venue|
|---|---|---|
|(**GFCI**) [A hybrid causal search algorithm for latent variable models](http://proceedings.mlr.press/v52/ogarrio16.pdf)|Ogarrio, Juan Miguel, Peter Spirtes, and Joe Ramsey|*Conference on Probabilistic Graphical Models* (**PGM**) 2016|

### Cause-effect pairs

#### Methods based on functional causal model

|Title|Authors|Venue|
|---|---|---|
|(**IGCI**) [Inferring deterministic causal relations](https://arxiv.org/abs/1203.3475)|Daniusis, Povilas, Dominik Janzing, Joris Mooij, Jakob Zscheischler, Bastian Steudel, Kun Zhang, and Bernhard Schölkopf|*conference on uncertainty in artificial intelligence* (**UAI**) 2010|
|(**PNL**) [On the identifiability of the post-nonlinear causal model](https://dl.acm.org/citation.cfm?id=1795190)|Zhang, Kun, and Aapo Hyvärinen|*conference on uncertainty in artificial intelligence* (**UAI**) 2009|
|(**ANM**) [Nonlinear causal discovery with additive noise models](http://papers.nips.cc/paper/3548-nonlinear-causal-discovery-with-additive-noise-models.pdf)|Hoyer, Patrik O., Dominik Janzing, Joris M. Mooij, Jonas Peters, and Bernhard Schölkopf|*Advances in neural information processing systems* (**NIPS**) 2009|

#### Methods based on complexity measure

* [A Generalization Error Bound for Multi-class Domain Generalization](https://arxiv.org/abs/1905.10392)  
Deshmukh, Aniket Anand, Yunwen Lei, Srinagesh Sharma, Urun Dogan, James W. Cutler, and Clayton Scott.  
*arXiv preprint arXiv:1905.10392* (2019).  
[[code]](https://www.dropbox.com/sh/bls758ro5762mtf/AACbn3UXJItY9uwtmCAdi7E3a?dl=0)


### arXiv

* [Domain generalization by marginal transfer learning](https://arxiv.org/abs/1711.07910)  
Blanchard, Gilles, Aniket Anand Deshmukh, Urun Dogan, Gyemin Lee, and Clayton Scott.  
*arXiv preprint arXiv:1711.07910* (2017).  
[[code]](https://github.com/aniketde/DomainGeneralizationMarginal)

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
1. <a name="1"></a> Gong, Boqing, Yuan Shi, Fei Sha, and Kristen Grauman. "Geodesic flow kernel for unsupervised domain adaptation." In Computer Vision and Pattern Recognition (CVPR), 2012 IEEE Conference on, pp. 2066-2073. IEEE, 2012.

2. <a name="2"></a> Everingham, Mark, Luc Van Gool, Christopher KI Williams, John Winn, and Andrew Zisserman. "The pascal visual object classes (voc) challenge." International journal of computer vision 88, no. 2 (2010): 303-338.

3. <a name="3"></a> Russell, Bryan C., Antonio Torralba, Kevin P. Murphy, and William T. Freeman. "LabelMe: a database and web-based tool for image annotation." International journal of computer vision 77, no. 1-3 (2008): 157-173.

4. <a name="4"></a> Griffin, Gregory, Alex Holub, and Pietro Perona. "Caltech-256 object category dataset." (2007).

5. <a name="5"></a> Choi, Myung Jin, Joseph J. Lim, Antonio Torralba, and Alan S. Willsky. "Exploiting hierarchical context on a large database of object categories." (2010).

-----

## Contact

* **Shoubo Hu** - shoubo [dot] sub [at] gmail [dot] com

See also the list of [contributors](https://github.com/amber0309/Domain-generalization/graphs/contributors) who participated in this project.

-----

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
