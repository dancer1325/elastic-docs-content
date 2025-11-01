---
navigation_title: Local installation (quickstart)
mapped_pages:
  - https://www.elastic.co/guide/en/elasticsearch/reference/current/run-elasticsearch-locally.html
applies_to:
  deployment:
    self:
products:
  - id: elasticsearch
---

# Local development installation (quickstart) [run-elasticsearch-locally]

* goal
  * ⚠️INSTRUCTIONS | ONLY local DEPLOYMENTS⚠️
    * ❌NOT use | production deployment❌
    * 1-month trial license / includes ALL Elastic features

## Prerequisites [local-dev-prerequisites]

* [download and install Docker Desktop](https://www.docker.com/products/docker-desktop)
* | Microsoft Windows,
  * install [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install)

## Step 1: Run `start-local` script [local-dev-quick-start]

* `curl -fsSL https://elastic.co/start-local | sh`
  * set up {{es}} & {{kib}} locally 
* | browser,
  * * **{{es}}**: [http://localhost:9200](http://localhost:9200)
  * **{{kib}}**: [http://localhost:5601](http://localhost:5601)

## Learn more [local-dev-additional-info]

* [Elastic's `start-local` setup](https://github.com/elastic/start-local)

## Next steps [local-dev-next-steps]

* [{{es}} basics](/elastic-docs-content/solutions/search/get-started/quickstarts.md) 
