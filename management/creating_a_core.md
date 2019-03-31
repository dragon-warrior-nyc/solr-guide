A Solr Core is a running instance of a Lucene index. 
We need to create a Solr Core to perform operations like indexing and analyzing.

A Solr application may contain one or multiple cores. 
If necessary, two cores in a Solr application can communicate with each other.

There are two ways to create a core in terminal:

1. using create command
```
bin/solr create -c my_first_solr_core
```
2. using create_core command
```
bin/solr create_core -c my_second_solr_core
```






