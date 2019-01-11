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
| 23 Aug 2018 | 6.5 release (14 Nov 2018) | 23 Feb 2020 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-4-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Dissect processor | A new processor that's fast and performant, and brings more processing power to the edge device |  |
| L | Azure module | Monitoring your Azure cloud environment using the Elastic Stack is a single command away | [blog post](https://www.elastic.co/blog/azure-cloud-monitoring-with-the-elastic-stack) |
| APM | ML integration | Click a button in the APM app to enable Machine Learning jobs and start detecting anomalies on performance and errors |  |
| APM | Java & Go agents | New APM agents for Java and Go |  |
| ES | Kerberos auth | Use Kerberos as authentication realm |  |
| ES | FIPS 140-2 | Elasticsearch now has the ability to run with a FIPS 140-2 enabled JVM |  |
| ES | Field alias | Create aliases on fields, no need to reindex anymore. Good to get prepared for [ECS](https://github.com/elastic/ecs) |  |
| ML | Custom rules | Custom rules for fine tuning machine learning results (to avoid learning or alerting on specific conditions) |  |

## 6.3

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 13 Jun 2018 | 6.4 release (23 Aug 2018) | 13 Dec 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-3-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | K8S and Docker autodiscovery | The Autodiscover feature allows logs & metrics to be captured automatically |  |
| B | syslog input | Send logs to Filebeat using syslog over UDP or TCP |  |
| L | Connecting pipelines | Multi-staged processing pipelines can connect pipelines within a Logstash process |  |
| APM | Watcher integration | Receive alerts on errors (in APM data) |  |
| ES | SQL | Query Elasticsearch using the SQL language, coming with a JDBC driver |  |
| ES | Rollups | Take historic data and generate aggregate statistics. Very useful for metrics in particular. |  |
| ML | CCS support | Machine Learning jobs now support Cross Cluster Search |  |
| K | Auto complete | Auto complete added in the Kibana Discover query bar |  |
| K | Index Management UI | Browse indices, see details about an individual, and change some options (close, force merge, clear cache, etc.) directly from the UI |  |

## 6.2

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 6 Feb 2018 | 6.3 release (13 Jun 2018) | 6 Aug 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-2-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Monitoring | Monitor Beats health in a new Kibana UI |  |
| B | Keystore | Hide passwords from configuration files using a secure keystore |  |
| L | Keystore | Hide passwords from configuration files using a secure keystore |  |
| L | JDBC static filter |  |  |
| ES | Rank Evaluation | Track how rankings of expected results is measured against specific queries |  |
| ES | SAML support | Get access to the Elastic Stack with the introduction of SAML support |  |
| ML | Calendar setting | Skip analyzing the data during scheduled events (entered manually or imported via ics) |  |
| K | Vega | Support for Vega & Vega lite visualizations |  |

## 6.1

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 13 Dec 2017 | 6.2 release (6 Feb 2018) | 13 Jun 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-1-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | TLS support | Packetbeat adds support for the TLS protocol to inspect the TLS enveloppe |  |
| L | Ruby filter | Complex modification of events in Logstash is now possible via the Logstash Ruby filter |  |
| APM | New! | APM released, with server, agents and UI | [blog post](https://www.elastic.co/blog/elastic-apm-beta-released) |
| ES | Split | Each original primary shard is split into two, or more, primary shards in the new index, as a companion to the Shrink Index API |  |
| ES | Composite agg | The composite aggregation is designed to return all terms and sorted in 'natural order' |  |
| ML | Forecasting | Based on the past, what values would you expect in the future |  |
| K | Input control | Input control visualization components allow users to select particular values and guide to important filtering values for a dashboard |  |

## 6.0

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 14 Nov 2017 | 6.1 release (13 Dec 2017) | 14 May 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-0-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Docker & K8S | Logs and metrics out of Kubernetes and Docker | [Blog post](https://www.elastic.co/blog/enrich-docker-logs-with-filebeat) |
| B | Auditbeat | A new beat to capture auditd (based on the Linux audit framework) |  |
| L | Pipelines | Run multiple pipelines concurrently for different use cases in the same instance, with centralized pipeline management, pipeline viewer and a conversion tool from ingest pipelines! | [doc](https://www.elastic.co/guide/en/logstash/6.0/multiple-pipelines.html), [Multiple pipelines](https://www.elastic.co/blog/logstash-multiple-pipelines), [Management UI](https://www.elastic.co/blog/logstash-centralized-pipeline-management), [Pipeline viewer](https://www.elastic.co/guide/en/logstash/6.0/logstash-pipeline-viewer.html) and [Conversion tool](https://www.elastic.co/blog/ingest-node-to-logstash-configuration-converter) |
| ES | Rolling upgrade | Upgrade a cluster without a cluster restart (from 5.6.3 to 6.x) |  |
| ES | Faster restart | Faster Restarts and Recoveries using operations-based shard recovery (using sequence IDs) |  |
| ES | Sparse data | sparse fields (with no data) in doc-values will be significantly smaller |  |
| ES | Distributed alerting | Distributed watch execution moves watch execution to the nodes that hold the shards of the watcher index | [Blog post](https://www.elastic.co/blog/distributed-watch-execution-elasticsearch-6.0) |
| ES | Removal of types | Indices now have only a single mapping type | [doc](https://www.elastic.co/guide/en/elasticsearch/reference/6.0/removal-of-types.html) |
| ES | Security | We no longer use `changeme` as a default password! And TLS/SSL between nodes is required when security is enabled |  | 
| K | Kuery Language | Try out the new Kibana Query Language | [Blog post](https://www.elastic.co/blog/building-a-better-search-experience-in-kibana) |
| K | CSV export | Search in Discovery then export matching documents as a CSV file via the reporting menu |  |
| K | Watcher UI | New UI for creating and editing alerts based on thresholds |  |
| K | Full screen & dashboard only | Enter full screen mode when viewing a dashboard and only share dashboards to users | [Blog post](https://www.elastic.co/blog/kibana-dashboard-only-mode) |
| K | Cluster Alerts | Alerts on Monitoring Email Notifications and License Expiration |  |

## 5.6

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 11 Sep 2017 | 7.0 release | 11 Mar 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-6-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| L | Modules | Logstash modules enable easy setup of Logstash configuration, index mapping in Elasticsearch & Kibana dashboards. Starting with two modules for Netflow and Arcsight  |  |
| ES | Rolling upgrade | Upgrade a cluster without a cluster restart (starting from 5.6.3) |  |
| K | Migration assistant | Prepare upgrades by inspecting breaking changes to index, cluster settings, etc |  |

## 5.5

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 6 Jul 2017 | 5.6 release (11 Sep 2017) | 6 Jan 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-5-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| L | Queueing | Dead Letter Queues enables local queueing in Logstash (when using Elasticsearch output) |  |
| ES | MSI installer | Windows MSI Installer for Elasticsearch with both GUI and silent installation support |  |
| ML | Monitoring | Monitor assigned nodes, number of processed documents, and a job's state over time |  |
| K | Filter editor | New filter editors (drop-downs, text-boxes) in Discover |  |
| K | Regions in maps | The Elastic Maps Service now supports region maps |  |
| K | Grok debugger | Debug grok patterns (from Logstash or ingest pipelines) in Kibana |  |


## 5.4

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 4 May 2017 | 5.5 release (6 Jul 2017) | 4 Nov 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-4-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| ML | New! | Machine Learning makes it easy to detect anomalies (spot infrastructure problems, cyber attacks, or business issues) by automatically modeling the normal behavior of time series data |  |
| K | Time Series Visual Builder | Time Series Visual Builder (TSVB) combines pipeline aggregations and a new UI for interacting with, and designing visualizations from, time series data |  |
| K | Watcher UI | 

## 5.3

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 28 Mar 2017 | 5.4 release (4 May 2017) | 28 Sep 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-3-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |

## 5.2

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 31 Jan 2017 | 5.3 release (28 Mar 2017) | 31 Jul 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-2-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |

## 5.1

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 5 Dec 2016 | 5.2 release (31 Jan 2017) | 8 Jun 2018 |

## 5.0

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 26 Oct 2016 | 5.1 release (5 Dec 2016) | 26 Apr 2018 |


## Authors

* **Vincent Maury** - *Initial commit* - [blookot](https://github.com/blookot)

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE.md](LICENSE.md) file for details
