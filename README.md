# FULL STACK IN NUTSHELL


# WHAT is REST API?

REST means Represential State Transfer

The server creates the representation of a resource to be responded back to a client. This representation is normally in the form of JSON/XML

1. Simple 
2. Scalable -> State Less 
3. Perfromace -> Caching

# What is CRUD?
Create Read Update Delete

Use HTTP method to accompalish CRUD 
C - POST
R - GET
U - PUT
D - DELETE

Also there is PATCH which is an update on parts of the existing object



# Database

## NoSql


## MongoDB

Type of data 

BSON not JSON
- Compact and 
- Traversable
- Integer 
- Decimal128
- Date
- Binary
- GeoJSON

### MongoDB Query API


db.collection.findOne()
Match a single document

db.collection.find()
- Return coursor

db.collection.aggregate()
- Aggregate


###

findOne( <query>, <projection>)

projection defines which field to take

db.movies.findOne({

},{
    "title":1 // Think 1 and 0, like inclue and not include
})


$match
$project
$sort
$limit


mongodb-pattern