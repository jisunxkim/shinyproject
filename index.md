---
title: "Machine Learning - Classification Methods"
subtitle: Project - Shiny Application and reproducible Pitch
author: "Jisun Kim"
job: null
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme: tomorrow
widgets: []
mode: selfcontained
knit: slidify::knit2slides
# github:
#   repo: shinyproject
#   user: jisunxkim
---

## Introduction to the Shiny App 
 Objective
- Introduce the two most common classification methods: k-means and Hierarchical Agglomerative
- Test the methods using mtcars from the R datasets
- Set different number of clusters which is important parameters for the methods

## How to use the app
Directions
- 1. pick a method
- 2. select number of class
- 3. explore data summary, cluster result and cluster plot tabs for the results


---
## k-means and Hierarchical Agglomerative
> - k-means:  
"K-means clustering is the most commonly used unsupervised machine learning algorithm for partitioning a given data set into a set of k groups (i.e. k clusters), where k represents the number of groups pre-specified by the analyst. It classifies objects in multiple groups (i.e., clusters), such that objects within the same cluster are as similar as possible (i.e., high intra-class similarity), whereas objects from different clusters are as dissimilar as possible (i.e., low inter-class similarity). In k-means clustering, each cluster is represented by its center (i.e, centroid) which corresponds to the mean of points assigned to the cluster."  
source: https://uc-r.github.io/kmeans_clustering  

> - Hierarchical Agglomerative:   
"The agglomerative clustering is the most common type of hierarchical clustering used to group objects in clusters based on their similarity. It's also known as AGNES (Agglomerative Nesting). The algorithm starts by treating each object as a singleton cluster. Next, pairs of clusters are successively merged until all clusters have been merged into one big cluster containing all objects. The result is a tree-based representation of the objects, named dendrogram.""  
source: https://www.datanovia.com/en/lessons/agglomerative-hierarchical-clustering/  


---
## Example - K-means
Data: mtcars, Number of Clusters: 3

![plot of chunk unnamed-chunk-1](figure/unnamed-chunk-1-1.png)

---
## Example - Hierarchical Agglomerative
Data: mtcars, Number of Clusters: 3

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2-1.png)

