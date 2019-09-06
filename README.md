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
    <td colspan="3" align="center"><b>With confounders</b></td>
  </tr>
  <tr>
    <td>(<b>FCI</b>)<a href="https://mitpress.mit.edu/books/causation-prediction-and-search-second-edition"> <i>Causation, prediction, and search</i></a></td>
    <td>Spirtes, Peter and Glymour, Clark N and Scheines, Richard and Heckerman, David and Meek, Christopher and Cooper, Gregory and Richardson, Thomas</td>
    <td>MIT press 2000</td>
  </tr>
</table>

<table>
  <tr>
    <td colspan="3" align="center"><b>Without confounder</b></td>
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

<table>
  <tr>
    <td colspan="3" align="center"><b>Without confounder</b></td>
  </tr>
  <tr>
    <td>(<b>PairwiseLiNGAM</b>)<a href="http://www.jmlr.org/papers/volume14/hyvarinen13a/hyvarinen13a.pdf"> Pairwise likelihood ratios for estimation of non-Gaussian structural equation models</a></td>
    <td>Hyvärinen, Aapo, and Stephen M. Smith</td>
    <td><i>Journal of machine learning research</i> <b>JMLR</b> 2011</td>
  </tr>
  <tr>
    <td>(<b>DirectLiNGAM</b>)<a href="http://www.jmlr.org/papers/volume12/shimizu11a/shimizu11a.pdf"> DirectLiNGAM: A direct method for learning a linear non-Gaussian structural equation model</a></td>
    <td>Shimizu, Shohei, Takanori Inazumi, Yasuhiro Sogawa, Aapo Hyvärinen, Yoshinobu Kawahara, Takashi Washio, Patrik O. Hoyer, and Kenneth Bollen</td>
    <td><i>Journal of machine learning research</i> <b>JMLR</b> 2011</td>
  </tr>
  <tr>
    <td>(<b>LiNGAM</b>)<a href="http://www.jmlr.org/papers/volume7/shimizu06a/shimizu06a.pdf"> A linear non-Gaussian acyclic model for causal discovery</a></td>
    <td>Shimizu, Shohei, Patrik O. Hoyer, Aapo Hyvärinen, and Antti Kerminen</td>
    <td><i>Journal of machine learning research</i> <b>JMLR</b> 2006</td>
  </tr>
</table>

#### Score-based methods

<table>
  <tr>
    <td colspan="3" align="center"><b>Without confounder</b></td>
  </tr>
  <tr>
    <td>(<b>fGES</b>)<a href="https://link.springer.com/article/10.1007/s41060-016-0032-z"> A million variables and more: the Fast Greedy Equivalence Search algorithm for learning high-dimensional graphical causal models, with an application to functional magnetic resonance images</a></td>
    <td>Ramsey, Joseph, Madelyn Glymour, Ruben Sanchez-Romero, and Clark Glymour</td>
    <td><i>International journal of data science and analytics</i> 2017</td>
  </tr>
  <tr>
    <td>(<b>GES</b>)<a href="http://www.jmlr.org/papers/v3/chickering02b.html"> Optimal Structure Identification With Greedy Search</a></td>
    <td>Chickering, David Maxwell</td>
    <td><i>Journal of machine learning research</i> <b>JMLR</b> 2002</td>
  </tr>
</table>

#### Hybrid methods

<table>
  <tr>
    <td colspan="3" align="center"><b>With confounders</b></td>
  </tr>
  <tr>
    <td>(<b>GFCI</b>)<a href="http://proceedings.mlr.press/v52/ogarrio16.pdf"> A hybrid causal search algorithm for latent variable models</a></td>
    <td>Ogarrio, Juan Miguel, Peter Spirtes, and Joe Ramsey</td>
    <td><i>Conference on Probabilistic Graphical Models</i> <b>PGM</b> 2016</td>
  </tr>
</table>

### Cause-effect pairs

#### Methods based on functional causal model

<table>
  <tr>
    <td colspan="3" align="center"><b>Without confounder</b></td>
  </tr>
  <tr>
    <td>(<b>IGCI</b>)<a href="https://arxiv.org/abs/1203.3475"> Inferring deterministic causal relations</a></td>
    <td>Daniusis, Povilas, Dominik Janzing, Joris Mooij, Jakob Zscheischler, Bastian Steudel, Kun Zhang, and Bernhard Schölkopf</td>
    <td><i>Conference on uncertainty in artificial intelligence</i> <b>UAI</b> 2010</td>
  </tr>
  <tr>
    <td>(<b>PNL</b>)<a href="https://dl.acm.org/citation.cfm?id=1795190"> On the identifiability of the post-nonlinear causal model</a></td>
    <td>Zhang, Kun, and Aapo Hyvärinen</td>
    <td><i>Conference on uncertainty in artificial intelligence</i> <b>UAI</b> 2009</td>
  </tr>
  <tr>
    <td>(<b>ANM</b>)<a href="http://papers.nips.cc/paper/3548-nonlinear-causal-discovery-with-additive-noise-models.pdf"> Nonlinear causal discovery with additive noise models</a></td>
    <td>Hoyer, Patrik O., Dominik Janzing, Joris M. Mooij, Jonas Peters, and Bernhard Schölkopf</td>
    <td><i>Advances in neural information processing systems</i> <b>NIPS</b> 2009</td>
  </tr>
</table>

#### Methods based on complexity measure

<table>
  <tr>
    <td colspan="3" align="center"><b>Without confounder</b></td>
  </tr>
  <tr>
    <td>(<b>CURE</b>)<a href="http://proceedings.mlr.press/v38/sgouritsa15.pdf"> Inference of cause and effect with unsupervised inverse regression</a></td>
    <td>Sgouritsa, Eleni, Dominik Janzing, Philipp Hennig, and Bernhard Schölkopf</td>
    <td><i>Artificial intelligence and statistics</i> <b>AISTATS</b> 2015</td>
  </tr>
  <tr>
    <td>(<b>GPI</b>)<a href="http://www.jmlr.org/papers/v3/chickering02b.html"> Probabilistic latent variable models for distinguishing between cause and effect</a></td>
    <td>Stegle, Oliver, Dominik Janzing, Kun Zhang, Joris M. Mooij, and Bernhard Schölkopf</td>
    <td><i>Advances in neural information processing systems</i> <b>NIPS</b> 2010</td>
  </tr>
</table>


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
