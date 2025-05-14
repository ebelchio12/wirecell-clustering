# Evaluation tool for Wire-Cell clustering


## Goal of the tool

A tool for evaluating the performance of WireCell clustering algorithm. Make a full chain of event generation, wirecell simulation, wirecell signal processing, wirecell imaging and wirecell clustering. Evaluate the performance of the clustering algorithm based on two metrics: charge-weighted efficiency and purity.

## Files list

1)	**Clustering v0_30_2.ipynb**
2)	**create_cluster_samples.sh**
3)	**main_cluster_eval.ipynb**
4)	**clustering_eval.ipynb**

## File details:

1)	**Clustering v0_30_2.ipynb**: General information on how to setup sbndcode, wirecell, larreco, etc.
2)	**create_cluster_samples.sh**: bash script to run a full chain of generation, simulation.., wirecell clustering. Usage: bash create_cluster_samples.sh 
3)	**main_cluster_eval.ipynb**: Driver notebook to run the evaluation of Wire-Cell clustering with the help of an external notebook (clustering_eval.ipynb).. You can define evaluation parameters on it. Usage: go to the top of the notebook, then click Run > Run All Cells.
4)	**clustering_eval.ipynb**: an internal notebook to be run by main_cluster_eval.ipynb. It is automatically run.

## How to get the code:

1)	git clone https://github.com/ebelchio12/wirecell-clustering.git

