# Entity Attribute Identification
This repository contains resources developed within the following paper:

    A. Dargahi Nobari, A. Askari, F. Hasibi, and M. Neshati. “Query Understanding via Entity Attribute Identification”,
	In proceedings of The 27th ACM International Conference on Information and Knowledge Management (CIKM ’18).
	
You may check the [paper](https://dl.acm.org/doi/10.1145/3269206.3269245) ([PDF](http://arashdargahi.com/wp-content/uploads/entity_attr.pdf)) for more information.


## Data
The entity attribute identification data collection and its corresponding qrels files are available under data directory. This directory is organized as follows:

- `queries.json`: 167 queries selected from the [DBpedia-Entity v2](http://tiny.cc/dbpedia-entity) collection. The procedure of selecting these queries is described in the paper.
- `qrel.txt`: TREC style qrels file.
- `runs`: run files of baselines and proposed model.

## Citation

Please cite the paper, If you used the codes in this repository:
```
@inproceedings{EAI2018,
author = {Dargahi Nobari, Arash and Askari, Arian and Hasibi, Faegheh and Neshati, Mahmood},
title = {Query Understanding via Entity Attribute Identification},
year = {2018},
isbn = {9781450360142},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3269206.3269245},
doi = {10.1145/3269206.3269245},
booktitle = {Proceedings of the 27th ACM International Conference on Information and Knowledge Management},
pages = {1759–1762},
numpages = {4},
keywords = {entity attributes, entity search, query understanding},
location = {Torino, Italy},
series = {CIKM '18}
}
```

