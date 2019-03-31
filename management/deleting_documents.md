# Deleting documents

## Deleting document by ID

```
bin/post -c my_first_solr_core delete.xml 
```

## Deleting documents by query

Delete documents satisfying certain criterion
```
<delete> 
   <query>city:Chennai</query> 
</delete>
```

Delete all documents
```
<delete> 
   <query>*:*</query> 
</delete>
```
