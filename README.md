# Algorithms-for-Massive-Datasets

This project aims at detecting similarity among pairs of textual
documents within a big data environment. As a first thing, a large
dataset collecting abstracts from the biomedical domain is tokenized,
lemmatized and curated for stop words removal. Then, for each couple
of articles, the Jaccard similarity is computed and the number of similar
pairs is investigated for different thresholds. Among all, those most
similar are furtherly analyzed to asses the accuracy of the result. 
Finally, to reduce the computational load, an alternative approach, based
on Locality Sensitive Hashing, is also provided. While the analysis is
performed over a small fraction of the dataset, the proposed solutions
are easily scalable. Indeed, they are conducted in a cluster-computing
framework as PySpark, specific for handling big data.

