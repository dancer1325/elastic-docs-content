---
mapped_pages:
  - https://www.elastic.co/guide/en/elasticsearch/reference/current/elasticsearch-intro-what-is-es.html
  - https://www.elastic.co/guide/en/elasticsearch/reference/current/elasticsearch-intro.html
  - https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html
  - https://www.elastic.co/guide/en/starting-with-the-elasticsearch-platform-and-its-solutions/current/index.html
products:
  - id: elasticsearch
  - id: elastic-stack
  - id: observability
  - id: security
applies_to:
  serverless:
  stack:
description: Learn the fundamentals of Elastic. Discover what Elastic offers, explore
  core concepts of the Elastic Stack, understand deployment options, and access
  training resources to get started.
---

# Elastic fundamentals

* goal
  * Elastic's products
    * core features
    * concepts
    * real-world use cases

## What is Elastic? [what-is-es]

* Elastic platform
    ![](images/elastic-platform.png)
  * == search + analytics + AI platform + observability & security solutions
    * open source 
    * Search AI platform
      * == search + generative AI
        * provides near real-time search & analysis

* Elastic
  * 's main solutions OR types of projects
    * [**{{es}}**](../solutions/search/get-started.md)
      * allows build, -- via -- {{es}}'s vector database, AI toolkit, & advanced retrieval capabilities, 
        * powerful search
        * RAG applications   
    * [**Elastic {{observability}}**](../solutions/observability/get-started.md)
      * | 1! UI, 
        * see applications, infrastructure's logs, metrics, traces, + other telemetry data
    * [**{{elastic-sec}}**](../solutions/security/get-started.md)
      * == SIEM + endpoint security + cloud security 
      * provide
        * tools / 
          * enable
            * threat detection
            * prevention, 
            * investigation
            * response

## Explore the fundamentals

* **[The {{stack}}](the-stack.md)**
  * == open-source tools
    * {{es}}, 
    * {{kib}}, 
    * {{beats}}, 
    * {{ls}}

* **[Deployment options](deployment-options.md)**
  * goal
    * ways to deploy Elastic
      * fully managed serverless solutions
      * self-managed installations

* **[Versioning and availability](versioning-availability.md)**
  * goal
    * Elastic 
      * versioning
      * feature availability

## Training resources

* [https://www.elastic.co/training](https://www.elastic.co/training)
* [Elasticsearch Engineer course](https://www.elastic.co/training/elasticsearch-engineer) 
* [demo gallery](https://www.elastic.co/demo-gallery) 
* [Beginner's Crash Course to {{stack}}](https://www.youtube.com/playlist?list=PL_mJOmq4zsHZYAyK606y7wjQtC0aoE6Es)
