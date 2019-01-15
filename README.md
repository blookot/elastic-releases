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
| APM | Distributed tracing | Distributed tracing gives an end-to-end trace on a request as it traverses multiple services | [video](https://youtu.be/Bz41KzRCM4g) |
| APM | Monitoring | APM monitoring lets you track the health of your Elastic APM deployments from the Kibana Monitoring app |  |
| ES | Cross Cluster Replication | Synchronization of indices across clusters | [doc](https://www.elastic.co/guide/en/elastic-stack-overview/6.5/ccr-getting-started.html) |
| ES | ODBC | Query Elasticsearch using the SQL API and the ODBC driver |  |
| ML | Multi-bucket span | Detect anomalies that span multiple buckets and adjust anomaly score accordingly |  |
| K | Canvas | Create and share live infographic style presentations of your Elasticsearch data | [demo video](https://youtu.be/fxA5GE1-V50), [preview at Elastic{ON}](https://youtu.be/NhJi-9DkvdI) |
| K | Spaces | Kibana Spaces organize your Kibana objects (for eg. visualizations and dashboards) into separate "spaces", and use RBAC to control which users have access to which space | [5mn video](https://youtu.be/RUMi5HUsWxM) |
| K | Sample data | Several datasets (with dashboard, canvas, etc) are available to start playing around in Kibana! | [5mn video](https://youtu.be/qg5_k4ogpzY), [another one](https://youtu.be/32NbRQHHAYQ), the [flights dataset](https://youtu.be/hMFWu1NfNMU) and the [e-commerce dataset](https://youtu.be/6_DrY9_bVDY) |
| K | Rollup UI | Management UI to configure and manage and visualize rollup indices (for metrics) |  |
| K | Data visualizer | This new UI (in ML tab) finds the structure of an uploaded file, generates the grok, ingest pipeline and mapping to eventually import data in Elasticsearch |  |
| K | Infra UI | The Infrastructure solution allows to easily navigate between logs and metrics activity on any specific host, pod, or container | [6mn video](https://youtu.be/t4Ny-tcMES4), [preview at Elastic{ON}](https://youtu.be/NzHGDyAQ2_Y) |
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
| APM | Java & Go agents | New APM agents for Java and Go | [5mn video](https://youtu.be/mm0sdldjeo0) |
| ES | Kerberos auth | Use Kerberos as authentication realm |  |
| ES | FIPS 140-2 | Elasticsearch now has the ability to run with a FIPS 140-2 enabled JVM |  |
| ES | Field alias | Create aliases on fields, no need to reindex anymore. Good to get prepared for [ECS](https://github.com/elastic/ecs) |  |
| ML | Custom rules | Custom rules for fine tuning machine learning results (to avoid learning or alerting on specific conditions) |  |

## 6.3

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 13 Jun 2018 | 6.4 release (23 Aug 2018) | 13 Dec 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-3-0-released), [Video](https://youtu.be/q9R7r4ncaPY)

Opening the code of X-Pack: [Webpage](https://www.elastic.co/products/x-pack/open), [Blog post](https://www.elastic.co/blog/doubling-down-on-open) and [Elastic{ON} announcement](https://youtu.be/gR3OhOnCMf8)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | K8S and Docker autodiscovery | The Autodiscover feature allows logs & metrics to be captured automatically | [blog post](https://www.elastic.co/blog/docker-and-kubernetes-hints-based-autodiscover-with-beats), [video](https://youtu.be/1-iUoWGfByE) |
| B | syslog input | Send logs to Filebeat using syslog over UDP or TCP |  |
| L | Connecting pipelines | Multi-staged processing pipelines can connect pipelines within a Logstash process |  |
| APM | Watcher integration | Receive alerts on errors (in APM data) |  |
| ES | SQL | Query Elasticsearch using the SQL language, coming with a JDBC driver |  |
| ES | Rollups | Take historic data and generate aggregate statistics. Very useful for metrics in particular | [video](https://youtu.be/I5-9x_pQ-Y0) |
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
| ES | Split API | Each original primary shard is split into two, or more, primary shards in the new index, as a companion to the Shrink Index API |  |
| ES | Composite agg | The composite aggregation is designed to return all terms and sorted in 'natural order' |  |
| ML | Forecasting | Based on the past, what values would you expect in the future | [video](https://youtu.be/wJVgh5knV4E) |
| K | Input control | Input control visualization components allow users to select particular values and guide to important filtering values for a dashboard | [video](https://youtu.be/W1w76rysykI) |

## 6.0

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 14 Nov 2017 | 6.1 release (13 Dec 2017) | 14 May 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-0-0-released), [Video (FR)](https://youtu.be/mL-2Uorq9-k)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Docker & K8S | Logs and metrics out of Kubernetes and Docker | [blog post](https://www.elastic.co/blog/enrich-docker-logs-with-filebeat), [5mn video](https://youtu.be/4E3-k0eFcj0) |
| B | Auditbeat | A new beat to capture auditd (based on the Linux audit framework) |  |
| L | Multiple pipelines | Run multiple pipelines concurrently for different use cases in the same instance, with centralized pipeline management, pipeline viewer and a conversion tool from ingest pipelines! | [doc](https://www.elastic.co/guide/en/logstash/6.0/multiple-pipelines.html), [blog post](https://www.elastic.co/blog/logstash-multiple-pipelines), [management UI](https://www.elastic.co/blog/logstash-centralized-pipeline-management), [pipeline viewer](https://www.elastic.co/guide/en/logstash/6.0/logstash-pipeline-viewer.html) and [conversion tool](https://www.elastic.co/blog/ingest-node-to-logstash-configuration-converter) |
| ES | Rolling upgrade | Upgrade a cluster without a cluster restart (from 5.6.3 to 6.x) |  |
| ES | Faster restart | Faster Restarts and Recoveries using operations-based shard recovery (using sequence IDs) |  |
| ES | Sparse data | sparse fields (with no data) in doc-values will be significantly smaller |  |
| ES | Distributed alerting | Distributed watch execution moves watch execution to the nodes that hold the shards of the watcher index | [Blog post](https://www.elastic.co/blog/distributed-watch-execution-elasticsearch-6.0) |
| ES | Removal of types | Indices now have only a single mapping type | [doc](https://www.elastic.co/guide/en/elasticsearch/reference/6.0/removal-of-types.html) |
| ES | Security | We no longer use `changeme` as a default password! And TLS/SSL between nodes is required when security is enabled |  | 
| K | Kuery Language | Try out the new Kibana Query Language | [blog post](https://www.elastic.co/blog/building-a-better-search-experience-in-kibana) |
| K | CSV export | Search in Discovery then export matching documents as a CSV file via the reporting menu | [video](https://youtu.be/Jd8-A3fIGjo) |
| K | Watcher UI | New UI for creating and editing alerts based on thresholds |  |
| K | Full screen & dashboard only | Enter full screen mode when viewing a dashboard and only share dashboards to users | [blog post](https://www.elastic.co/blog/kibana-dashboard-only-mode), [video](https://youtu.be/lZoSL1usU_Y) |
| K | Cluster Alerts | Alerts on Monitoring Email Notifications and License Expiration |  |

## 5.6

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 11 Sep 2017 | 7.0 release | 11 Mar 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-6-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| L | Modules | Logstash modules enable easy setup of Logstash configuration, index mapping in Elasticsearch & Kibana dashboards. Starting with two modules for Netflow and Arcsight  | [doc](https://www.elastic.co/guide/en/logstash/5.6/logstash-modules.html) |
| ES | Rolling upgrade | Upgrade a cluster without a cluster restart (starting from 5.6.3) |  |
| ES | Java High-level client | New Java high-level REST client (built on top of the low-level client) accepts objects for the most important APIs |  |
| ES | Join datatype | New way to specify parent/child relationships without needing types | [doc](https://www.elastic.co/guide/en/elasticsearch/reference/5.6/parent-join.html) |
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
| K | Grok debugger | Debug grok patterns (from Logstash or ingest pipelines) in Kibana | [video](https://youtu.be/SKSqPRwDfns) |
| K | CCS support | Index Patterns can now point to indices from remote clusters using cross cluster search feature |  |


## 5.4

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 4 May 2017 | 5.5 release (6 Jul 2017) | 4 Nov 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-4-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Modules | Modules for JMX (using Jolokia) to monitor Java applications, Linux auditd and system authentication logs |  |
| ML | New! | Machine Learning makes it easy to detect anomalies (spot infrastructure problems, cyber attacks, or business issues) by automatically modeling the normal behavior of time series data |  |
| K | Time Series Visual Builder | Time Series Visual Builder (TSVB) combines pipeline aggregations and a new UI for interacting with, and designing visualizations from, time series data | [demo](https://www.elastic.co/elasticon/conf/2017/sf/kibana-visualizations-deep-dive), [video part1](https://youtu.be/CNR-4kZ6v_E), [video part2](https://youtu.be/CvorsH3x7Z8), [video part3](https://youtu.be/xkluflzhpAw) |
| K | Watcher UI | Watcher UI allows you to do basic operations on watches |  |

## 5.3

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 28 Mar 2017 | 5.4 release (4 May 2017) | 28 Sep 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-3-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Filebeat modules | Introducing modules (filebeat config, ES template and K dashboards) for Apache2, MySQL, Nginx, and System | [video](https://youtu.be/K-jVrLMOd-g) |
| B | Dynamic config reload | Dynamic configuration reloading makes it possible to change any module configuration on the fly without restarting the Beat |  |
| ES | CCS | Cross-cluster search, aka searching across multiple clusters, replacing the tribe node |  |


## 5.2

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 31 Jan 2017 | 5.3 release (28 Mar 2017) | 31 Jul 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-2-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Heartbeat | Heartbeat periodically checks the status of services (availability and round-trip-time) |  |
| B | Prometheus exporter | Prometheus module that collects metrics from the Prometheus exporters |  |
| K | LS Monitoring UI | New monitoring UI with nice graphs and historical data to track changes in your production Logstash instances |  [video](https://youtu.be/Ahfymloitjk) |
| K | Heatmaps | Heatmaps are great to pick out an area of high or low volume in time series data |  |

## 5.1

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 8 Dec 2016 | 5.2 release (31 Jan 2017) | 8 Jun 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-1-1-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Docker module | Periodically collect container metrics from cgroup | [blog post](https://www.elastic.co/blog/monitoring_container_resource_usage_with_metricbeat) |
| B | Kafka module | Connects to the local Kafka node and reads periodically details about the partitions |  |
| L | Presistent queues | Inbuilt persistent queues enable Logstash to persist events before processing them |  |
| L | Truncate | Truncate is a new filter that allows you to truncate fields longer than a given byte-length |  |
| ES | Faster reindexing | Reindex can now perform their tasks in parallel automatically |  |
| K | Tag cloud | New visualization displaying tags (words) as a cloud |  |
| K | Advanced monitoring | Advanced view in monitoring and more charts in index and node views |  |
| K | Search profiler | Get detailed information about the parts of your queries that take time |  |

## 5.0

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 26 Oct 2016 | 5.1 release (5 Dec 2016) | 26 Apr 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-0-0-released), [Intro video](https://youtu.be/_XPCb9FdgNs), [Feature tour](https://youtu.be/ttO6_BRSEE4), [Kibana 5 video](https://youtu.be/TBvlDrt7b70)

"ELK" becomes "The Elastic Stack", see [Webpage](https://www.elastic.co/elk-stack) 

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Metricbeat | Metricbeat replaces Topbeat as the primary tool for collecting metrics |  |
| B | Kafka output | Native Kafka output support in Beats |  |
| L | Monitoring | New monitoring feature provides runtime visibility into the Logstash pipeline  |  |
| ES | Ingest node | Ingest Node is an Elasticsearch node type enabling some data enrichment capabilities at index time | [blog post](https://www.elastic.co/blog/new-way-to-ingest-part-1) |
| ES | Painless scripting | New scripting language for query, alert, reindex, or in an ingest node for a powerful way to manipulate documents | [blog post](https://www.elastic.co/blog/painless-a-new-scripting-language), [video](https://youtu.be/3FLEJJ8PsM4) |
| ES | Keyword field | Analyzed and not-analysed string fields have been replaced by dedicated `text` fields for full text search, and `keyword` fields for string identifier search, sorting, and aggregations |  |
| ES | Shrink API | Shrink an existing index into a new index with fewer primary shards |  |
| ES | Rollover API | Rolls an alias over to a new index when too large or too old | [blog post](https://www.elastic.co/blog/managing-time-based-indices-efficiently) |
| ES | Java Low-level client | A simple low-level Java HTTP/REST client |  |
| ES | Benchmarking | We open sourced our Elasticsearch benchmarking tool Rally | [doc](https://github.com/elastic/rally) |
| K | Timelion | New visualization tool with query DSL and interesting math functions and rendering capabilities | [video](https://youtu.be/cfTehOJScL4) |
| K | Console | Build free-form requests to Elasticsearch from Kibana (replacing Sense) |  |
| K | Security UI | Management UI in Kibana for creating and managing both users and roles |  |
| K | Kibana monitoring | Monitoring for Kibana as part of the monitoring (Marvel) UI |  |
| K | Scripted fields | Create computed scripted fields in Kibana using Painless | [video](https://youtu.be/BhmpDtS7g28) |

## Authors

* **Vincent Maury** - *Initial commit* - [blookot](https://github.com/blookot)

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE.md](LICENSE.md) file for details
