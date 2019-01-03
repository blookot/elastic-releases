# Elastic releases
Listing releases of the Elastic stack with new features and references

**Disclamer**: This is an unofficial informative document. Vincent Maury or Elastic cannot be held responsible for erroneous information. Official information can be found on the only official [Elastic website](https://www.elastic.co).


## 6.5

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 14 Nov 2018 | 6.6 release | 14 May 2020 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-5-0-released), [Video](https://youtu.be/dnmqoD0XP18)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Central management | Enroll, configure, and manage Beats deployments from a central place using either the UI or API |  |
| B | Functionbeat | Functionbeat is a new Beat that deploys as a function in serverless platform, and streams cloud infrastructure data to Elasticsearch |  |
| APM | Distributed tracing | Distributed tracing gives an end-to-end trace on a request as it traverses multiple services |  |
| APM | Monitoring | APM monitoring lets you track the health of your Elastic APM deployments from the Kibana Monitoring app |  |
| ES | Cross Cluster Replication | Synchronization of indices across clusters | [doc](https://www.elastic.co/guide/en/elastic-stack-overview/6.5/ccr-getting-started.html) |
| ES | ODBC | Query Elasticsearch using the SQL API and the ODBC driver |  |
| ML | Multi-bucket span | Detect anomalies that span multiple buckets and adjust anomaly score accordingly |  |
| K | Canvas | Create and share live infographic style presentations of your Elasticsearch data | [demo video](https://youtu.be/fxA5GE1-V50) |
| K | Spaces | Kibana Spaces organize your Kibana objects (for eg. visualizations and dashboards) into separate "spaces", and use RBAC to control which users have access to which space |  |
| K | Rollup UI | Management UI to configure and manage and visualize rollup indices (for metrics) |  |
| K | Data visualizer | This new UI (in ML tab) finds the structure of an uploaded file, generates the grok, ingest pipeline and mapping to eventually import data in Elasticsearch |  |
| K | Infra UI | The Infrastructure solution allows to easily navigate between logs and metrics activity on any specific host, pod, or container |  |
| K | Logs UI | The Logs UI in Kibana displays live trail, like a `tail -f` combined with a grep |  |

## 6.4

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 23 Aug 2018 | 14 Nov 2018 | 23 Feb 2020 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-4-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| APM | ML integration | Click a button in the APM app to enable Machine Learning jobs and start detecting anomalies on performance and errors |  |
| APM | Java & Go agents | New APM agents for Java and Go |  |
| ES | Kerberos auth | Use Kerberos as authentication realm |  |
| ES | FIPS 140-2 | Elasticsearch now has the ability to run with a FIPS 140-2 enabled JVM |  |
| ES | Field alias | Create aliases on fields, no need to reindex anymore. Good to get prepared for [ECS](https://github.com/elastic/ecs) |  |
| ML | Custom rules | Custom rules for fine tuning machine learning results (to avoid learning or alerting on specific conditions) |  |


## Authors

* **Vincent Maury** - *Initial commit* - [blookot](https://github.com/blookot)

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE.md](LICENSE.md) file for details
