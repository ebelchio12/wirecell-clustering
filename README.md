# Wire-Cell clustering evaluation tool


## Goal of the tool

Have a tool to evaluate the performance of WireCell clustering algorithm. Make a full chain of event generation, wirecell simulation, wirecell signal processing, wirecell imaging and wirecell clustering. Evaluate the performance of the clustering algorithm based on two metrics: charge-weighted efficiency and purity.

## Files list

1)	Clustering v0_30_2.ipynb
2)	create_cluster_samples.sh
3)	main_cluster_eval.ipynb
4)	clustering_eval.ipynb

## File details:

1)	General information on how to setup sbndcode, wirecell, larreco, etc.
2)	bash script to run a full chain of generation, simulation.., wirecell clustering. Usage: bash create_cluster_samples.sh 
3)	Driver notebook to run an external notebook (clustering_eval.ipynb). You can define evaluation parameters on it. Usage: go to the top of the notebook, then click Run > Run All Cells.
4)	an internal notebook to be run by main_cluster_eval.ipynb. It is automatically run.

## How to get the code:

1)	Git clone 

