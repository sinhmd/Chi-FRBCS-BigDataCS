
# Chi-FRBCS-BigDataCS: MapReduce implementation of the basic Chi et al.’s algorithm for imbalanced big data

The Chi-FRBCS-BigDataCS algorithm is an approach that can be used to classify imbalanced bigdata. It is a MapReduce design where each map process is responsible for building a Rule Base using only the data included in its portion and where the reduce process is responsible for collecting and combining the Rule Base generated by each mapper to form the final Rule Base. This algorithm is divided into two different phases: the first phase is devoted to the creation of the model, Figure 1, and the second part is devoted to the estimation the class associated to a dataset. Both phases follow the MapReduce structure distributing all the computations needed along several processing units that manage different chunks of information, aggregating the results obtained in an appropriate manner.

Figure 1: A flowchart of how the building of the KB is organized in Chi-FRBCS-BigDataCS.

<img src=http://sci2s.ugr.es/sites/default/files/files/TematicWebSites/BigData/building_chi_job.png width=731 height=403 />

# References

V. López, S. Río, J.M. Benítez, F. Herrera. Cost-Sensitive Linguistic Fuzzy Rule Based Classification Systems under the MapReduce Framework for Imbalanced Big Data. Fuzzy Sets and Systems 258 (2015) 5-38. http://doi: 10.1016/j.fss.2014.01.015 [link to pdf file](http://sci2s.ugr.es/sites/default/files/ficherosPublicaciones/1734_2015-lopez-FSS.pdf)
