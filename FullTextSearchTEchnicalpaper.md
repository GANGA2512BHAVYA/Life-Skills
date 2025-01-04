
# Full Text Search
Full-text search is a technique that finds information in a large amount of text by analyzing the content of documnents, rather than just matchig keywords.
# Features
- Relevance ranking
- fuzzy searching
- phrase matchig
- handling synonyms
## Tools for Full Text Search
There are many tools for implementing full-text search across various applications and use cases.
Some of them are  
1. Elasticsearch
2. Apache solr
3. MySQL
4. Lucene and many more

# Lucene:
Lucene is a powerful Java search library that lets you easily add search or Information Retrieval(IR) to applications.

## Features:
- Scalable & High-performance indexing
- Powerful, Accurate and Efficient Search Algorithms
- Cross platform solution
    - open source & 100% pure Java
    - Implementations in other programming languages available that are index-compatible.


# Elasticsearch
Elasticsearch is built on Apache Lucene.It is a distributed database where data is stored as JSON documnets. Distributed database means where data can run in multiple nodes(servers) at a time. 
JSON documnents store data like rows in datatable.

### Data in datatable:

|              Employee Table              |
-------------------------------------------|
| Name | Location | Age | email            |
|John  | HYD      | 27  | john56@gmail.com |

### Data in Elasticsearch:
Elasticsearch has index. It is a collection of JSON documnents. 

 ### JSON documnent: 

{  
    "name": "John",  
    "locaton": "HYD",  
    "Age": 26,  
    "Email":"john56@gmail.com"  
}

* Elasticsearch stores data in a database called inverted index, where data is literally stored as searches. This makes querying very fast even if vast amounts of data storage.

### Advantages:
1. Distributed database.
2. Horizontally Scalable, i.e., the database can run in multiple servers(nodes).
3. It is designed for faster queries. 
4. It supports many data types like text, number, Geo-spatial, IP addresses etc 

# Solr Search:
It is an open source search platform written in Java from Apache Lucene project.

## Features:
- Full text search: Searching documnents in full text database rather than metadata.
- Hit higlighting: Term search
- Faceted search: Search as per faceted classification.
- Real-time indexing.
- Dynamic clustering: Can have nodes.
- Database integration

#### Note: 
    Among all other full text search tools Elasticsearch and Solr Search are popular because of thier Speed and Scalability, Advanced Features, Flexibility and much more.

### References: 
https://www.youtube.com/watch?v=upvaxy7zj60 
https://www.youtube.com/watch?v=ykYjt7VA0t8&t=91s



