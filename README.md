# Attributed_Graph_Data
This is a repository for the data of binary attributed graph. The original non-attributed graphs can be downloaded from [https://github.com/
SotirisTsioutsiouliklis/FairLaR/](https://github.com/SotirisTsioutsiouliklis/FairLaR/), [networkrepository.com/](networkrepository.com), [snap.stanford.edu](snap.stanford.edu) We construct attribute graphs by randomly assigning attributes to vertices with approximately equal probability.

## aminer

dblp_aminer is a real dataset. It includes tens of thousands scholars and pictures their social network. The binary attribute is about gender, while 0 represents female and 1 represents male.

## dblp_DB/AI

This is a dataset extracted from dblp data. 

This undirected graph represents the cooperative relationship between scholars. If two scholars have published the same paper, there is an edge between the two corresponding points, otherwise there is no.

The binary attribute is about the number of published papers, while if a scholar has published more papers in the area of database than that of AI, the corresponding attribute is 1, otherwise is 0.

## dblp_DB/DM

The graph is totally the same with dblp_DB/DM. The only difference is attribute. If a scholar has published more papers in the area of database than that of DM, the corresponding attribute is 1, otherwise is 0.

## dblp_year

The graph is totally the same with dblp_DB/DM. The only difference is attribute. If a scholar published his first paper before 2008, the corresponding attribute is 1, meaning he/she is a senior scholar, otherwise is 0.

## NBA

This is a real dataset. This undirected graph represents the cooperative relationship between NBA players.The binary attribute is about nationalities. If a player is from America, the corresponding attribute is 0, otherwise is 1.

## IMDB

This is a real dataset. This undirected graph represents the cooperations between various actors and actress. The attribute setting in this graph is that, if an actor/actress was born before 1990, the attribute is 1 means he/she is a new actor/actress, otherwise is 0 means veteran actor/actress.
