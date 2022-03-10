# Investigation of Elasticsearch, Solr and Lucene for full text searching

## Abstract
Searches are integral parts of any application. Performing searches on terabytes and petabytes of data can be challenging when speed, performance, and high availability are core requirements.This paper investigate **Elasticsearch,Solr and Lucene**

## About **Apache Solr** 

[Apache](https://solr.apache.org/) Solr is an open-source search server built on top of Lucene that provides all of Lucene’s search capabilities through HTTP requests. It has been around for almost a decade and a half, making it a mature product with a broad user community.

Solr offers powerful features such as distributed full-text search, faceting, near real-time indexing, high availability, NoSQL features, integrations with big data tools such as Hadoop, and the ability to handle rich-text documents such as Word and PDF

### List of key features:
1. Full-text search 
1. Highlight 
1. Multi-array Search 
1. Real-time indexing 
1. Dynamic Clustering 
1. Database integration 
1. NoSQL functionality and productive document handling (e.g. words and PDF files)

## About Elasticsearch
[Elasticsearch](https://www.elastic.co/what-is/elasticsearch) is also an open-source search engine built on top of Apache Lucene, as the rest of the ELK Stack,  including Logstash and Kibana. It extends Lucene’s powerful indexing and search functionalities using RESTful APIs, and it archives the distribution of data on multiple servers using the index and shards concept. Elasticsearch is completely based on JSON and is suitable for time series and NoSQL data.

This tool is much younger than Solr, but it has gained a lot of popularity because of its feature-rich use cases. Some of its primary features include distributed full-text distributed search, high availability, powerful query DSL, multitenancy, Geo Search, and horizontal scaling.

### List of key features:
 1. Distributed Search 
 1. Multi-lease period 
 1. A string of Analyzers 
 1. Scan Search 
 1. Group Aggregation 

## About Apache Lucene

[Apache Lucene](https://lucene.apache.org/) is a high-performance, full-featured search engine library written entirely in Java. It is a technology suitable for nearly any application that requires structured search, full-text search, faceting, nearest-neighbor search across high-dimensionality vectors, spell correction or query suggestions.

 Distributed Search 
 Multi-lease period 
 A string of Analyzers 
 Scan Search 
 Group Aggregation 

 ### List of key features:

 1. Provides ranked searching — i.e. best results returned first.
1. Supports many powerful    query types: phrase queries, wildcard queries, proximity queries, range queries and more.
1. Provides fielded searching (e.g. title, author, contents).
1. Supports sorting by any field.
Supports multiple-index searching with merged results.
1. It allows simultaneous update and searching.
Has flexible faceting, highlighting, joins and result grouping.
1. It is fast, memory-efficient and typo-tolerant suggesters.

## Conclusion
Apache Lucene is a high-performance, full-featured text search engine library written entirely in Java. It is a technology suitable for nearly any application that requires full-text search, especially cross-platform. It offers implementation of algorithms for creating indexes and doing search and ranking of documents based on query. Its provides a very sophisticated querying model and support document faceting as well.

Apache Solr and Elasticsearch are the search engines implemented using Lucene library. Using the featured provided by Lucene both have great job in making search and analysis easy and developer friendly. Both has very competitive features like:

Both expose API end points for indexing and searching content.
Both support structured and unstructured content.
Both have means to connect with data sources.
Both supports very comprehensive data aggregations some of which are not even supported by Lucene directly.
Both have ways to define and customizing data schema and indexes.
Both are distributed in nature and hence can handle scale easily.
Both can provide near real time search with high availability.
However there are still use cases where these two products are differ:

Solr started as a search engine on top of Lucene. Though it is still open source but it is embedded into a commercial product by Lucidworks which can provide enterprise search by connecting to various data sources.

Elasticsearch again is open source and being projected as more of a analytics engine as well. It also being embedded into commercial products by Elastic to cater to host of other use cases like log analysis, machine learning etc.

Both products have backing of tech companies founded by their developers. In my opinion both products are truly amazing and are no better in terms of performance than other because of underlying Lucene being a common denominator. If I have to choose one, I will go with one which I find easy to integrate with my work.

## References
1. [https://www.trustradius.com/compare-products/apache-lucene-vs-elasticsearch](https://www.trustradius.com/compare-products/apache-lucene-vs-elasticsearch)
1. [https://logz.io/blog/solr-vs-elasticsearch/](https://logz.io/blog/solr-vs-elasticsearch/)
1. [https://sematext.com/blog/solr-vs-elasticsearch-differences/](https://sematext.com/blog/solr-vs-elasticsearch-differences/)
1. [https://comparisons.financesonline.com/apache-lucene-vs-apache-solr](https://comparisons.financesonline.com/apache-lucene-vs-apache-solr)
1. [https://www.hcltech.com/blogs/elasticsearch-vs-solr](https://www.hcltech.com/blogs/elasticsearch-vs-solr)