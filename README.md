# Mongo C Driver

mongo-c-driver is a project that includes two libraries:

- libmongoc, a client library written in C for MongoDB.
- libbson, a library providing useful routines related to building, parsing, and iterating BSON documents.

# 🔨 Building

## 🐧 Linux

```
cmake -DENABLE_ZLIB=BUNDLED -DENABLE_SSL=OFF .
make
sudo make install
```
