# Learn-MongoDB

Language Reference for Mongo DB NoSQL

# Language Reference

use myDatabase - Select the database to use, created if not already in existence

db.items.insertOne(
  {
    Name: "Desk",
    Barcode: 3123433448041,
    Color: "Brown"
  }
)

- inserts a Document into a Collection (eg. the specified items into the items collection in myDatabase). items Collection is created if not alreayd in existence.


db.items.find() - Return all documents from items collection
