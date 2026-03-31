# Assignment-3-MongoDB-Setup-and-Queries

In Mongosh
```
use sample_mflix
db.movies.find({"runtime":{$gt:200},"year":1983})
```
![image](https://github.com/Etling-S/Assignment-3-MongoDB-Setup-and-Queries/blob/main/Screenshot_1_Assignment_3.png)
```
use sample_mflix
db.movies.find({"year":{$gt:2014},'imdb.rating':{$gt:9}})
```


![image](https://github.com/Etling-S/Assignment-3-MongoDB-Setup-and-Queries/blob/main/Screenshot_2_Assignment_3.png)

