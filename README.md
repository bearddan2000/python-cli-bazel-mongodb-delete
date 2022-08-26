# python-cli-bazel-mongodb-delete

## Description
A pymongo example w/o login.
Creates a single collection `weapon`
inside `test` database. Inserts multiple
records then prints the whole
collection and the collections inside
`test` database.
Deletes a single record.

## Tech stack
- bazel
- python
- mongodb

## Docker stack
- l.gcr.io/google/bazel:latest

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

# Credits
[Examples](https://www.kite.com/python/docs/pymongo.collection.Collection.delete_one)
