## What is MongoDB?

MongoDB is a document database with the scalability and flexibility that you want with the querying and indexing that you need.

## What is a Database?

A database holds a set of collections. A database typically has a separate file system directory to hold its data. Each database gets its own set of files on the file system. Generally, you associate a database with one application.

## What is a Collection?

A collection is a group of documents. If a document is the MongoDB analog of a row in a relational database table, then a collection is the analog of a table.

## What is a Document?

A record in MongoDB is a document, which is a data structure composed of field and value pairs. MongoDB documents are similar to JSON objects. The values of fields may include other documents, arrays, and arrays of documents.

## What is a Field?

A document has a dynamic schema. Dynamic schemas allow documents in the same collection to have different sets of fields and to have different field names for the common fields.

## What is a Primary Key?

In MongoDB, each document stored in a collection requires a unique _id field that acts as a primary key. If an inserted document omits the _id field, the MongoDB driver automatically generates an ObjectId for the _id field.

## Why use NoSQL?

NoSQL databases are built to allow the insertion of data without a predefined schema. This makes NoSQL databases ideal for storing and processing unstructured data.

## Why use MongoDB?

MongoDB is a document database, which means it stores data in JSON-like documents. We believe this is the most natural way to think about data, and is much more expressive and powerful than the traditional row/column model.
