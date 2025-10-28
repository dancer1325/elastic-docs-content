---
mapped_pages:
  - https://www.elastic.co/guide/en/elasticsearch/reference/current/elasticsearch-intro-what-is-es.html
products:
  - id: elasticsearch
---

# Use cases [introduction]
$$$what-is-kib$$$
$$$what-is-es$$$

## Elasticsearch

- **Full-text search**:
  - == build a full-text search solution
    - -- via -- inverted indexes + tokenization + text analysis
    - fast
    - relevant 
- **Vector database**
  - Store and search vectorized data
  - create vector embeddings /
    - have 
      - built-in natural language processing (NLP) models
      - third-party natural language processing (NLP) models
- **Semantic search**
  - goal
    - understand -- , via synonyms, dense vector embeddings, and learned sparse query-document expansion, --search queries' intent and contextual meaning
- **Hybrid search**
  - == full-text search + vector search -- via -- state-of-the-art ranking algorithms
- **Build search experiences**
  - add hybrid search capabilities | apps or websites
  - build enterprise search engines -- over -- your organization’s internal data sources
- **Retrieval augmented generation (RAG)**
  - {{ecloud}} (as a retrieval engine) -- to -- supplement generative AI models  
- **Geospatial search**
  - -- based on -- geospatial queries, 
    - search for locations
    - calculate spatial relationships 

[**Get started with {{es}} →**](../solutions/search/get-started.md)

## Observability

- **Logs, metrics, and traces**
  - Collect, store, and analyze logs, metrics, and traces from applications, systems, and services.
- **Application performance monitoring (APM)**
  - Monitor and analyze the performance of business-critical software applications.
- **Real user monitoring (RUM)**
  - Monitor, quantify, and analyze user interactions with web applications.
- **OpenTelemetry**
  - Reuse your existing instrumentation to send telemetry data to the Elastic Stack using the OpenTelemetry standard.

[**Get started with {{observability}} →**](../solutions/observability/get-started.md)

## Security

- **Security information and event management (SIEM)**
  - Collect, store, and analyze security data from applications, systems, and services.
- **Endpoint security**
  - Monitor and analyze endpoint security data.
- **Threat hunting**
  - Search and analyze data to detect and respond to security threats.

[**Get started with {{elastic-sec}} →**](../solutions/security/get-started.md)

Refer to Elastic [customer success stories](https://www.elastic.co/customers/success-stories) for concrete examples across a range of industries.

% TODO: cleanup these links, consolidate with Explore and analyze

$$$visualize-and-analyze$$$
$$$extend-your-use-case$$$
$$$_manage_your_data$$$
$$$_alert_and_take_action$$$
$$$organize-and-secure$$$
$$$organize-in-spaces$$$
$$$_organize_your_content_with_tags$$$
$$$intro-kibana-Security$$$
$$$_log_in$$$
$$$extend-your-use-case$$$
$$$try-kibana$$$
$$$_view_all_kib_has_to_offer$$$
$$$_audit_access$$$
$$$_secure_access$$$
