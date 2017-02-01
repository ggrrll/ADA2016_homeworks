

Review notes based on [ADA lectures](http://ada.epfl.ch/lectures/)

# STATS

## how to choose statistical test 
- [long table](http://sites.stat.psu.edu/~ajw13/stat500_su_res/notes/lesson14/images/summary_table.pdf) of the example suggested by pirroh

- nice [wiki review table](https://en.wikipedia.org/wiki/Statistical_hypothesis_testing#Common_test_statistics)

- here is a [decision tree](http://www.biochemia-medica.com/system/files/Marusteri_M._Statistical_test_selection_when_comparing_groups_Fig._4.jpg) suggested by  pirrow, and here
[another nice one](https://s-media-cache-ak0.pinimg.com/originals/da/c9/60/dac96086a651aea01b0ef24da4faaa9f.jpg)


# MACHINE LEARNING

## good practise in applied ML

- don't forget to:
	- standardize (bad point: assume gaussian!)
	- re-scale (bad point: too importance to outliers!)

- feature selection:
	- filtering (~prune) 
	- wrapper (~enrich) - usually slow

##  Supervised learning (good & fast algo)


- decision trees --> improveded to:
 
	- random forest (bagging)  - tend to high variance / overfit
	- B.D.T (boosting)	- tend to high bias

- k-nn (find best _k_)

- linerar regression - don't forget R2!

- [Choosing the right estimator](http://scikit-learn.org/stable/tutorial/machine_learning_map/) in scikit-learning

##  Unsupervised learning 

- Hierarchical - [Hierarchical on scikit](http://scikit-learn.org/stable/modules/clustering.html#hierarchical-clustering) and 
[on scipy](https://joernhees.de/blog/2015/08/26/scipy-hierarchical-clustering-and-dendrogram-tutorial/)

- point assignement

- DBScan - [DBScan on scikit](http://scikit-learn.org/stable/auto_examples/cluster/plot_dbscan.html#sphx-glr-auto-examples-cluster-plot-dbscan-py)

- Matrix Factorization 


# VIZ

## colors palette

- in [this webiste](http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3) 
you can find the code if you favourite color ;)

# TEXT   




# GRAPH


- community detection - e.g.: try to print modulartity VS # clusters



















