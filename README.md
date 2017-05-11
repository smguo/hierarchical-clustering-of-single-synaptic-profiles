# hierarchical-clustering-of-single-synaptic-profiles
*Performs hierarchical clustering using Seaborn "clustermap" function on synaptic features

The script loads the synaptic features from the MAT files, concatenates the features from 
the same well or from the same replicate together (depending on the value of "split_wells"), 
subsamples the synapses if the sample size is too large, standardizes the features, and 
performs hierachical clustering. The clustering result was represented using dendrograms 
and heatmaps.  
