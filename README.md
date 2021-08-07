# TypeDataset
Knowledge graphs with entity types and relation types, which is built on DBpedia dataset.

DB8k-28 is built based on DBpedia dataset. We require entities to have a title, abstract and type (i.e., rdfs:label, rdfs:comment predicates and rdfs:category). On this condition, we randomly select the dataset with 28 relations, 65 entity types, 8,258 nodes and 222,395 triples (named DB8k-28). According to the data division method of FB15k-237, we divide DB8k-28 into training set, validation set and test set at a ratio of approximately 88%, 6% and 6%.

Similarly, DB170k-256 is also built based on DBpedia dataset. Unlike DB8k-28, DB170k-256 is a large knowledge graph with 274 entity types and 256 relation types, 172,754 nodes and 2,939,952 triples dataset (named DB170k-256). According to the data division method of FB15k-237, we divide DB170k-256 into training set, validation set and test set at a ratio of approximately 88%, 6% and 6%.

There are descriptions of some files as follows:

node2singletype.txt，which is a set of the single type corresponding to each entity.

singletype2id.txt, which is a set of the id of each singletype.

multipletype2id.txt, which is a set of the multiple types corresponding to each entity.

types2id.txt, which is a set of the single type in multiple types corresponding to each entity.

node2count.txt, which is a set of the statistical frequency of multiple types corresponding to each entity.

node_info.txt, which is a set of all the information corresponding to each entity. Note that we only select part of the information for training.
