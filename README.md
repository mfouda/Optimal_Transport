> Hi, this repository is aimed to record my personal progresses and plan on the research of O.T.\
> I think the most helpful part for you may be the **Awesome Materials on Optimal Transport**, where I have maken some comments to help you choose the most suitable material.

# Research Schedule
#### 03/09 - 03/15
- [ ] Read [Paper 7](https://arxiv.org/pdf/1805.09114.pdf), [Paper 9](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6494675)
- [ ] Read [Lectures on Spectral Graph Theory](https://eclass.uoa.gr/modules/document/file.php/MATH506/03.%20%CE%98%CE%AD%CE%BC%CE%B1%CF%84%CE%B1%20%CE%B5%CF%81%CE%B3%CE%B1%CF%83%CE%B9%CF%8E%CE%BD/cbms.pdf)
- [x] Read [Paper 6](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8347162), [Paper 8](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6409473)

#### 03/02 - 03/08
- [x] Review and Read [O.T. in Structured Domains: Algorithms and Applications](http://people.csail.mit.edu/davidam/assets/publications/PhD_thesis/PhDThesis.pdf)
- [x] Read [A Brief Lecture on Submodular Functions](https://www2.isye.gatech.edu/~atoriello3/submod.pdf), [Factor Analysis](https://www.stat.cmu.edu/~cshalizi/350/lectures/12/lecture-12.pdf)
- [x] Read [Paper 3](https://papers.nips.cc/paper/9539-got-an-optimal-transport-framework-for-graph-comparison.pdf), [Paper 4](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7552590), [Paper 5](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8700665)

#### 02/21 - 03/01
- [x] Finish learning the code | [POT](https://github.com/rflamary/POT)
- [x] 02/28 Read [Paper 2](https://papers.nips.cc/paper/6792-near-linear-time-approximation-algorithms-for-optimal-transport-via-sinkhorn-iteration.pdf) and play with corresponding code
- [x] 02/26 Read [Paper 1](https://papers.nips.cc/paper/4927-sinkhorn-distances-lightspeed-computation-of-optimal-transport.pdf) and play with corresponding code
- [x] 02/24 Finish the first three chapters | [O.T. in Structured Domains: Algorithms and Applications](http://people.csail.mit.edu/davidam/assets/publications/PhD_thesis/PhDThesis.pdf)
- ~~-[ ] Read [Paper 3](https://arxiv.org/pdf/1607.05816.pdf%3E%60__), [Paper 4](https://arxiv.org/pdf/1610.06519.pdf%3E%60__)~~

#### 02/17 - 02/18
- [x] 02/18 Finish a mindmap of Intro. to O.T. | [Mindmap](./images/Mindmap_Intro_ot.png)
- [x] 02/18 Review the whole introduction | [Intro. to Optimal Transport](http://www.math.cmu.edu/~mthorpe/OTNotes)

#### 02/10 - 02/16
- [x] 02/15 Finish the NIPS2017 Tutorial | [A Primer on O.T.](https://nips.cc/Conferences/2017/ScheduleMultitrack?event=8736)
- [x] 02/15 Finish the tutorial | [Intro. to Optimal Transport](http://www.math.cmu.edu/~mthorpe/OTNotes)

# Awesome Materials on Optimal Transport

### Introductory Materials / Tutorials / Textbooks
| Materials  | Comments (Possibly Helpful) |
|---|---|
| [Introduction to Optimal Transport (Thorpe)](http://www.math.cmu.edu/~mthorpe/OTNotes) | This introduction is full of theorems and proofs, which are based on some definitions and theorems from rigorous probability theory, functional analysis and convex analysis. In addition, it doesn't mention Sinkhorn's Algorithm, Barycenters, and some other latest topics. [[Mindmap]](./images/Mindmap_Intro_ot.png) |
| [Intro. to O.T. (Santambrogio)](https://arxiv.org/pdf/1009.3856.pdf) | Update |
| [Computational Optimal Transport](https://optimaltransport.github.io/)  | The slide is not complete in some sections, so it is better to read the corresponding book. [[Book]](https://arxiv.org/pdf/1803.00567.pdf)  [[Codes]](https://github.com/optimaltransport/optimaltransport.github.io/tree/master/code)  [[Slides]](https://optimaltransport.github.io/slides-peyre/CourseOT.pdf) |
| [A Primer on Optimal Transport](https://nips.cc/Conferences/2017/ScheduleMultitrack?event=8736) | This is a tutorial of O.T. in NIPS2017 which can give an overall outline about the research of O.T. up to 2017. |
| [Optimal transport: Old and New](https://cedricvillani.org/sites/dev/files/old_images/2012/08/preprint-1.pdf) | Textbook, Published in 2008 |
| [Optimal Transport for Applied Mathematicians](http://www.math.toronto.edu/~mccann/assignments/477/Santambrogio15.pdf)| Textbook, Published in 2015 |
| [Optimal Transport in Biomedical Imaging](http://imagedatascience.com/transport/tutorials_miccai18.html) | Update |
| [A User’s Guide to Optimal Transport](https://webusers.imj-prg.fr/~nicola.gigli/Site/Publications_files/users_guide%20-%20final.pdf) | Mainly on the Riemannian geometry |

### Papers
| Papers  | Comments  |
|---|---|
| [On minimum Kantorovich distance estimators (2006)](https://www.sciencedirect.com/science/article/pii/S0167715206000381) | Use Wasserstein distances to define a loss between data and model. |
| [Sinkhorn Distances: Lightspeed Computation of Optimal Transport (2013)](https://papers.nips.cc/paper/4927-sinkhorn-distances-lightspeed-computation-of-optimal-transport.pdf) | Proposed a widely used algorithm for solving optimal transport problems. |
| [Optimal mass transport: Signal processing and machine-learning applications (2017)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7974883) | A short review of applications in O.T. |
| [Near-linear time approximation algorithms for optimal transport via Sinkhorn iteration (2017)](https://papers.nips.cc/paper/6792-near-linear-time-approximation-algorithms-for-optimal-transport-via-sinkhorn-iteration.pdf) | Proposed a coordinated descent version of Sinkhorn algorithm which is of linear time. |
| [Structured Optimal Transport (2018)](http://people.csail.mit.edu/davidam/assets/publications/2018_structured_ot/AISTATS2018_Structured.pdf) | Use cost function to encode the structure information |
| [A Geometric View of Optimal Transportation and Generative Model (2018)](https://www.sciencedirect.com/science/article/pii/S0167839618301249) | Update |
| [Optimal Transport and Information Geometry (2019)](https://arxiv.org/pdf/1906.00030.pdf) | Update |
| [Dynamic Graph CNN for Learning on Point Clouds (2019)](https://dl.acm.org/doi/pdf/10.1145/3326362)| Update |
| [A Geometric Understanding of Deep Learning (2020)](https://www.sciencedirect.com/science/article/pii/S2095809919302279) | Update |

#### Graph Comparison with Optimal Transport
| Papers  | Comments  |
|---|---|
| [Learning Laplacian Matrix in Smooth Graph Signal Representations (2016)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7552590) | Learning graph laplacian matrix using smooth graph signal, where graph laplacian matrices uniquely charaterizes graphs |
| [Matching Node Embeddings for Graph Similarity (2017)](http://shichuan.org/hin/topic/Embedding/2017.%20AAAI%20Matching%20Node%20Embeddings%20for%20Graph%20Similarity.pdf) | Update |
| [Learning Graphs from Data (2019) ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8700665) | An overview of graph learning methods. It mentions three methods: statistical method, physical method, and graph signal processing method |
| [Optimal Transport for structured data with application on graphs (2019)](https://arxiv.org/pdf/1805.09114.pdf) | Update |
| [GOT: An Optimal Transport framework for Graph comparison (2019)](https://papers.nips.cc/paper/9539-got-an-optimal-transport-framework-for-graph-comparison.pdf) | Compare graph using their smooth graph signals |

### Courses / Seminars / Workshop
- [OTML2014](http://www.iip.ist.i.kyoto-u.ac.jp/OTML2014/doku.php)
- [OTML2017](http://otml17.marcocuturi.net/)
- [OTML2019](https://sites.google.com/view/otml2019/home?authuser=0)
- [Optimal Transport & Information Geometry Reading Course Spring 2019](https://dsweber2.github.io/Optimal-Transport-Information-Geometry/)

### Programming Library
- [Python Optimal Transport Library](https://buildmedia.readthedocs.org/media/pdf/pot/latest/pot.pdf)
