h1 hi

```js
docker-compose -f docker-compose.yml -f docker-compose.dev.yml up -d

for production, rebuild
docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d --build
docker-compose -f docker-compose.yml -f docker-compose.dev.yml

docker exec -it plugin_mongo_1 mongo -u "admin" -p "admin"
show dbs
use mydb

db.books.insert({"name": "harry potter"})
db.books.find()

```
