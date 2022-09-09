# MongoDB Docker-Compose Template

## Start and Stop

```sh
docker-compose up
docker-compose down
```

## Shell commands

Enter container

```sh
docker exec -it mongodb bash
```

```sh
# log into mongo shell as admin
mongo admin -u admin -p
# or log in as user1
mongo mydb -u user1 -p
# then enter password

# show current database name
db.getName()

# insert to collection
db.table1.insert({ "foo": "foo1" })
db.table2.insert({ "bar": "bar1" })

# list databases
show dbs

# list collections
show collections
```
