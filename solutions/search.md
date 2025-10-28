---
mapped_pages:
  - https://www.elastic.co/guide/en/elasticsearch/reference/current/search-with-elasticsearch.html
  - https://www.elastic.co/guide/en/serverless/current/what-is-elasticsearch-serverless.html
  - https://www.elastic.co/guide/en/kibana/current/search-space.html
applies_to:
  stack:
  serverless:
products:
  - id: elasticsearch
  - id: cloud-serverless
  - id: kibana
---

# Elasticsearch

* {{es}}
  * enables you to
    * build -- ,via Elastic's unified platform, -- powerful search experiences for websites, applications, and enterprise data 

## Use cases

| Use case                             | Business goals                                                     | Technical requirements                                        |
| ------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------- |
| **Vector search/hybrid search** | Run nearest neighbour search, combine with text for hybrid results | Dense embeddings, sparse embeddings, combined with text/BM25       |
| **Ecommerce/product catalog search** | Provide fast, relevant, and up-to-date results, faceted navigation | Inventory sync, user behavior tracking, results caching       |
| **Workplace/knowledge base search**  | Search across range of data sources, enforcing permissions         | Third-party connectors, document-level security, role mapping |
| **Website search**                   | Deliver relevant, up-to-date results                               | Web crawling, incremental indexing, query caching             |
| **Customer support search**          | Surface relevant solutions, manage access controls, track metrics  | Knowledge graph, role-based access, analytics                 |
| **Chatbots/RAG**                     | Enable natural conversations, provide context, maintain knowledge  | Vector search, ML models, knowledge base integration          |
| **Geospatial search**                | Process location queries, sort by proximity, filter by area        | Geo-mapping, spatial indexing, distance calculations          |

## {{es-serverless}} [elasticsearch-serverless]
```{applies_to}
serverless:
  elasticsearch: ga
```

* {{es-serverless}} 
  * == [{{serverless-full}}](../deploy-manage/deploy.md)'s project type
  * enables you to
    * use the {{es}}'s core functionality: searching, indexing, storing, and analyzing data

* see
  - [{{serverless-full}} vs other deployment types](../deploy-manage/deploy/elastic-cloud/differences-from-other-elasticsearch-offerings.md) 
  - [Billing](../deploy-manage/cloud-organization/billing/elasticsearch-billing-dimensions.md)
