# Assignment-3-MongoDB-Setup-and-Queries

In Mongosh
```
use sample_mflix
db.movies.find({"year":{$gt:2014},'imdb.rating':{$gt:9}})

db.movies.find({"runtime":{$gt:200},"year":1983})
```
