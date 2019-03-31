Index documents in sample.csv/sample.json/sample.xml to my_first_solr_core:
```
bin/post -c my_first_solr_core sample.csv 
```
```
bin/post -c my_first_solr_core sample.json 
```
```
bin/post -c my_first_solr_core sample.xml 
```

View the documents from the index:
```
http://localhost:8983/solr/my_first_solr_core/select?q=*:*
```

Note that if you do this again. 
```
bin/post -c my_first_solr_core sample.csv 
```

The documents in the index by default will not be overrides. Instead, they will be added as new documents in the index. 

How to revise then?
