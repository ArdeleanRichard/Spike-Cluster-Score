# Spike-Cluster-Score
Spike Cluster Score (SCS) is a clustering performance metric designed with the purpose of spike sorting in mind. Like Purity, it will evaluate the clustering of each sample as its own cluster as a perfect clustering. SCS was developed to not punish overclustering, as overclustering is acceptable for some applications. SCS was developed as underclustering was considered unacceptable and Purity did not penalise enough the underclustering of K-Means and DBSCAN. As a result, the score of Purity was similar across all algorithms. It is the user’s responsibility to evaluate how much overclustering is acceptable for each dataset. Clustering each sample as its own cluster will receive a perfect score but will not provide information. We recommend using SCS together with other performance evaluation metrics, while taking into consideration the weaknesses of each metric.

SCS was published in Frontiers in Computational Neuroscience, alongside with a clustering algorithm.

## Citation
We would appreciate it, if you cite the paper when you use this work:

- For Plain Text:
```
E.-R. Ardelean, A.-M. Ichim, M. Dînşoreanu, and R. C. Mureşan, “Improved space breakdown method – A robust clustering technique for spike sorting,” Frontiers in Computational Neuroscience, vol. 17, 2023, doi: 10.3389/fncom.2023.1019637.
```

- BibTex:
```
@ARTICLE{10.3389/fncom.2023.1019637,
AUTHOR={Ardelean, Eugen-Richard and Ichim, Ana-Maria and Dînşoreanu, Mihaela and Mureşan, Raul Cristian},   
TITLE={Improved space breakdown method – A robust clustering technique for spike sorting},      
JOURNAL={Frontiers in Computational Neuroscience},      
VOLUME={17},           
YEAR={2023},      
URL={https://www.frontiersin.org/articles/10.3389/fncom.2023.1019637},       
DOI={10.3389/fncom.2023.1019637}      
}
```