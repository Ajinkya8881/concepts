# Full Text Search Improvement Using Elasticsearch, Solr and Lucene

## Introduction
In the project I joined, we started facing performance and scaling issues while running search queries. The existing database was not efficient for full text search, especially when the data increased. Because of this, search results became slow. To solve this, I explored tools that are specifically designed for full text search.

## Technologies Overview

### Apache Lucene
* Low level Java library  
* Very powerful but needs more coding  
* Gives full control to developers  

### Apache Solr
* Built on Lucene  
* Provides REST APIs  
* Easier to use than Lucene  

### Elasticsearch
* Also built on Lucene  
* Designed for distributed systems  
* Fast and scalable  
* Works well with large data  

## Comparison

* Lucene → More control, more effort  
* Solr → Stable and structured search  
* Elasticsearch → Scalable and fast  

## Conclusion
After comparing all three, Elasticsearch is the best option for this project. It improves search speed, handles large data efficiently, and scales easily as the system grows.

## References

* https://www.elastic.co/what-is/elasticsearch  
* https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html  
* https://solr.apache.org/guide/solr/latest/getting-started/solr-tutorial.html  
* https://lucene.apache.org/core/9_9_0/core/index.html   
