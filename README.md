# Tool for evaluation of Wire-Cell clustering


## Goal

A tool for evaluating the performance of WireCell clustering algorithm. Make a full chain of sample generation, wirecell simulation, signal processing, imaging and clustering. Evaluate the performance of the clustering algorithm based on two metrics: charge-weighted efficiency and purity.

## File details:

- **Clustering v0_30_2.ipynb**
  - General information on how to setup sbndcode, larreco, wirecell, etc. Look at this notebook first.

- **create_cluster_samples.sh**
  - bash script to run a full chain of sample generation, wirecell simulation, signal processing, imaging and clustering. Saves output in .txt format for clustering evaluation.
    - Usage: *bash create_cluster_samples.sh*

- **main_cluster_eval.ipynb**
  - Driver notebook to run the evaluation of Wire-Cell clustering with the help of an external notebook (clustering_eval.ipynb).. You can define evaluation parameters on it.
    - Usage: download the code on your gpvm area.
   
- **clustering_eval.ipynb**
  - an internal notebook to be run by main_cluster_eval.ipynb. It is automatically run.

## How to get the code:

1)	git clone https://github.com/ebelchio12/wirecell-clustering.git

