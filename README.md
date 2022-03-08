# Investigation of Elasticsearch, Solr and Lucene for full text searching

Searches are integral parts of any application. Performing searches on terabytes and petabytes of data can be challenging when speed, performance, and high availability are core requirements.This paper investigate **Elasticsearch,Solr and Lucene**

## About **Apache Solr** 

[Apache](https://solr.apache.org/) Solr is an open-source search server built on top of Lucene that provides all of Lucene’s search capabilities through HTTP requests. It has been around for almost a decade and a half, making it a mature product with a broad user community.

Solr offers powerful features such as distributed full-text search, faceting, near real-time indexing, high availability, NoSQL features, integrations with big data tools such as Hadoop, and the ability to handle rich-text documents such as Word and PDF

## About Elasticsearch
[Elasticsearch](https://www.elastic.co/what-is/elasticsearch) is also an open-source search engine built on top of Apache Lucene, as the rest of the ELK Stack,  including Logstash and Kibana. It extends Lucene’s powerful indexing and search functionalities using RESTful APIs, and it archives the distribution of data on multiple servers using the index and shards concept. Elasticsearch is completely based on JSON and is suitable for time series and NoSQL data.

This tool is much younger than Solr, but it has gained a lot of popularity because of its feature-rich use cases. Some of its primary features include distributed full-text distributed search, high availability, powerful query DSL, multitenancy, Geo Search, and horizontal scaling.

## About Apache Lucene

[Apache Lucene](https://lucene.apache.org/) is a high-performance, full-featured search engine library written entirely in Java. It is a technology suitable for nearly any application that requires structured search, full-text search, faceting, nearest-neighbor search across high-dimensionality vectors, spell correction or query suggestions.

