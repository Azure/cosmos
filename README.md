Azure Cosmos DB is a fully managed database service with turnkey global distribution and transparent multi-master replication. Get single-digit millisecond read and write latencies at the 99th percentile, automatic and elastic scaling of throughput and storage worldwide, 99.999-percent high availability, and five well-defined consistency choices—all backed by industry-leading comprehensive SLAs.

This repo is primarily a hub for linking to relevant GitHub repos for Azure Cosmos DB. It also contains some common engineering docs for use by the Cosmos DB engineering team.

# Azure Cosmos DB

## Getting started 🎉
To get started with Azure Cosmos DB, checkout [docs.microsoft.com](https://docs.microsoft.com/en-us/azure/cosmos-db/).

## Getting support 🛠

For help:
 - See our [docs](https://docs.microsoft.com/en-us/azure/cosmos-db/) (especially the troubleshooting section)
 - [Open a support ticket](https://azure.microsoft.com/en-us/support/create-ticket/)
 - Email askcosmosdb@microsoft.com
 - Open an issue in the appropriate repo below

This GitHub repo is not intended to provide support for Azure Cosmos DB. (hence why issues are disabled)

## Repos 👩‍💻

|Repo|Description|Langauge/Platform|API|
|-|-|-|-|
|[azure-cosmos-dotnet-v2](https://github.com/Azure/azure-cosmos-dotnet-v2)| Legacy .NET v2 SDK for SQL API | .NET | SQL |
|[azure-cosmos-dotnet-v3](https://github.com/azure/azure-cosmos-dotnet-v3)| Newest .NET v3 SDK for SQL API | .NET | SQL |
|[azure-cosmosdb-java](https://github.com/azure/azure-cosmosdb-java) | Java Async SDK for SQL API | Java | SQL |
|[azure-documentdb-java](https://github.com/Azure/azure-documentdb-java) | Legacy Java Sync SDK for SQL API | Java | SQL |
|[azure-cosmos-js](https://github.com/azure/azure-cosmos-js) | @azure/cosmos JavaScript SDK for SQL API |JS | SQL |
|[cosmos-sign](https://github.com/Azure/cosmos-sign) | Utility library for signing Azure Cosmos tokens and generating headers | JS | SQL
|[azure-cosmosdb-node](https://github.com/Azure/azure-cosmosdb-node) | Legacy documentdb JavaScript SDK for SQL API | JS | SQL |
|[azure-cosmos-python](https://github.com/azure/azure-cosmos-python) | Python SDK for SQL API | Python | SQL |
|[azure-cosmos-table-python](https://github.com/Azure/azure-cosmos-table-python) | Python SDK for Table API | Python | SQL |
|[spring-data-cosmos](https://github.com/Microsoft/spring-data-cosmosdb)| Spring Data Connector for Cosmos DB SQL API | Java/Spring | SQL |
|[azure-cosmosdb-spark](https://github.com/Azure/azure-cosmosdb-spark) | Apache Spark Connector for Azure Cosmos DB | Apache Spark | SQL 
|[azure-cosmos-cassandra-extensions](https://github.com/Azure/azure-cosmos-cassandra-extensions) | Azure Cosmos extensions for Apache Cassandra (retry/etc.) | Java | Cassandra |
|[azure-cosmosdb-js-server](https://github.com/Azure/azure-cosmosdb-js-server) | Server-side JS scripting samples | JS | SQL |
|[azure-cosmos-tla](https://github.com/Azure/azure-cosmos-tla) | Azure Cosmos TLA+ specifications | TLA | All |
|[azure-cosmos-db-emulator-docker](https://github.com/Azure/azure-cosmos-db-emulator-docker) | Contains Dockerfiles for the Azure Cosmos DB Emulator | Docker | All |
|[cosmos-sql-language-service](https://github.com/Azure/cosmos-sql-language-service) | Cosmos DB SQL Language Service for the Monaco editor | Language Service | SQL |
|[kafka-connect-cosmosdb-graph](https://github.com/Azure/kafka-connect-cosmosdb-graph) | Apache Kafka connector for Cosmos DB Gremlin API | Kafka | Gremlin |
|[Microsoft.Extensions.Caching.Cosmos](https://github.com/Azure/Microsoft.Extensions.Caching.Cosmos) | Microsoft.Extensions.Caching.Cosmos | .NET/ASP.NET | SQL |

## Project boards 📅

- [Cosmos DB SDK team board](https://github.com/orgs/Azure/projects/31)

# Contributing 🤝

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
