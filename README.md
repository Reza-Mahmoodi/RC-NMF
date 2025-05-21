## A Regularized Convex Nonnegative Matrix Factorization Model for signed network analysis (2021)
- Authors = Wang, Jia and Mu, Rongjian
- Journal = Social Network Analysis and Mining
### Abstract
Community detection and link prediction are two basic tasks of complex network system analysis, which are widely used in the detection of telecom fraud organizations and recommendation systems in the real world. In ordinary unsigned networks, these two analyses have been developed for a long time. However, due to the existence of negative edges, the study of community detection and link prediction in signed networks is still limited now. Most existing methods have high computational complexity and ignore the generation of the networks based on heuristics. In this paper, we propose a regularized convex nonnegative matrix factorization model (RC-NMF) from the perspective of the generative model to detection communities in the signed network. This algorithm introduces graph regularization to constrain nodes with negative edges into different communities and nodes with positive edges into the same communities as much as possible. Experiments on synthetic signed networks and several real-world signed networks validate the effectiveness and accuracy of the proposed approach both in community detection and link prediction.

If you find this implementation helpful in your work, please consider citing both the original paper and our related research on **Link prediction by adversarial NMF**:

## Original Paper:

```
@article{wang2021regularized,
  title={A regularized convex nonnegative matrix factorization model for signed network analysis},
  author={Wang, Jia and Mu, Rongjian},
  journal={Social Network Analysis and Mining},
  volume={11},
  number={1},
  pages={7},
  year={2021},
  publisher={Springer}
}
```

## Our Paper:
```
@article{mahmoodi2023link,
  title={Link prediction by adversarial nonnegative matrix factorization},
  author={Mahmoodi, Reza and Seyedi, Seyed Amjad and Tab, Fardin Akhlaghian and Abdollahpouri, Alireza},
  journal={Knowledge-Based Systems},
  volume={280},
  pages={110998},
  year={2023},
  publisher={Elsevier}
}
```
