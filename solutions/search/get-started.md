---
mapped_pages:
  - https://www.elastic.co/guide/en/elasticsearch/reference/current/getting-started.html
  - https://www.elastic.co/guide/en/serverless/current/elasticsearch-get-started.html
applies_to:
  stack:
  serverless:
    elasticsearch: all
products:
  - id: elasticsearch
  - id: cloud-serverless
navigation_title: Get started
description: To try out an {{es}} project or solution, pick your deployment type, search goals, and ingestion method.
---

# Get started with {{es}}

* goal
  * build a search experience -- by -- 
    * setting up your first deployment,
    * refining your search goals,
    * adding data

* steps
  * choose your [deployment type](../../deploy-manage/deploy.md#choosing-your-deployment-type)
    * [self-managed](../../deploy-manage/deploy/self-managed/)
      * _Example:_ [local development installation](../../deploy-manage/deploy/self-managed/local-development-installation-quickstart.md)
    * Elastic-managed options
    * [{{es-serverless}}](../search.md#es-serverless-elasticsearch-serverless)
      * MORE simple and fast
  * create an [{{es-serverless}} project](../../deploy-manage/deploy/_snippets/create-serverless-project-intro.md)
  * choose the {{es}} project type
  * provide a name

* TODO:
:::::{step} Identify your search goals
Depending on your use case, you can choose multiple [search approaches](search-approaches.md), for example full-text and semantic search.
Each approach affects your options for storing and querying your data.

If you're unsure which approaches match your goals, you can try them out with sample data. For example, [](/solutions/search/get-started/semantic-search.md).

If you prefer to ingest your data first and transform or reindex it as needed later, skip to the next step.
:::::
:::::{{step}} Ingest your data

If your goals include vector or semantic AI-powered search, create vectorized data with built-in and third-party natural language processing (NLP) models and store it in an {{es}} vector database.
The approach that requires the least configuration involves adding `semantic_text` fields when ingesting your data.
This method is described in [](/solutions/search/semantic-search/semantic-search-semantic-text.md).

To learn about adding data for other search goals, go to [](/solutions/search/ingest-for-search.md).
For a broader overview of ingestion options, go to [](/manage-data/ingest.md).

If you're not ready to add your own data, you can use [sample data](/manage-data/ingest/sample-data.md) or create small data sets when you follow the instructions in the [quickstarts](/solutions/search/get-started/quickstarts.md).

The {{es}} home page in the UI also provides workflow guides for creating indices and ready-to-use code examples for ingesting data by using REST APIs.
:::::
:::::{{step}} Build your search queries

Your next steps will be to choose a method to write queries and interact with {{es}}.
You can pick a programming language [client](/reference/elasticsearch-clients/index.md) that matches your application and choose which [query languages](/solutions/search/querying-for-search.md) you will use to express your search logic.
Each decision builds on the previous ones, offering flexibility to mix and match approaches based on your needs.

Not sure where to start exploring?
Get an introduction to [index and search basics](/solutions/search/get-started/index-basics.md) or [build your first search query with Python](/solutions/search/get-started/keyword-search-python.md).
:::::
::::::

## Related resources

Use these resources to learn more about {{es}} or get started in a different way:

- [](/deploy-manage/deploy/deployment-comparison.md)
- [Get started with Query DSL search and filters](elasticsearch://reference/query-languages/query-dsl/full-text-filter-tutorial.md)
- [Get started with ES|QL queries](elasticsearch://reference/query-languages/esql/esql-getting-started.md)
- [Analyze eCommerce data with aggregations using Query DSL](/explore-analyze/query-filter/aggregations/tutorial-analyze-ecommerce-data-with-aggregations-using-query-dsl.md)
