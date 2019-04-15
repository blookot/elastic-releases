# Elastic releases
Listing releases of the Elastic stack with new features and references

**Disclamer**: This is an unofficial informative document. Vincent Maury or Elastic cannot be held responsible for erroneous information. Official information can be found on the only official [Elastic website](https://www.elastic.co).



## 7.0

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 10 Apr 2019 | 7.1 release | 10 Oct 2020 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-7-0-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | ECS | Beats now use the new field naming convention Elastic Common Schema (ECS) | [blog post](https://www.elastic.co/blog/introducing-the-elastic-common-schema), [webinar](https://www.elastic.co/webinars/introducing-the-elastic-common-schema), [ECS doc](https://www.elastic.co/guide/en/ecs/current/index.html) |
| B | AWS module | New metricbeat module to monitor AWS EC2 using Cloudwatch | [video](https://youtu.be/JO-1PhA7XuU), [blog post](https://www.elastic.co/blog/monitoring-aws-ec2-using-metricbeat-and-the-elastic-stack) |
| B | MSSQL module | New metricbeat module for Microsoft SQL Server |  |
| B | OpenMetrics support | Deeper integration between Elastic Stack and Prometheus by support the OpenMetrics standard | [blog post](https://www.elastic.co/blog/elasticsearch-observability-embracing-prometheus-and-openmetrics-standards-for-metrics), [observability, by Elastic](https://www.elastic.co/blog/observability-with-the-elastic-stack) |
| L | Java execution | Logstash now executed in Java by default, for better performance, less memory and java plugins support | [blog post](https://www.elastic.co/blog/meet-the-new-logstash-java-execution-engine), [java plugins](https://www.elastic.co/blog/previewing-native-support-for-java-plugins-in-logstash) |
| ES | Typeless APIs | 6.0: no more than one type, 7.0: new typeless APIs, 8.0 will remove APIs that accept types | [blog post](https://www.elastic.co/blog/moving-from-types-to-typeless-apis-in-elasticsearch-7-0) |
| ES | Cluster coordination | New Zen2 cluster coordination which is faster, safer, and easier to use | [blog post](https://www.elastic.co/blog/a-new-era-for-cluster-coordination-in-elasticsearch) |
| ES | Circuit breaker | Adding a real memory circuit breaker which detects unserviceable requests to improve node resiliency | [blog post](https://www.elastic.co/blog/improving-node-resiliency-with-the-real-memory-circuit-breaker) |
| ES | Adaptive Replica Selection | Instead of basic round robin, ARS allows requests to be sent to the most available shard (and node) based on response time and queue size | [blog post](https://www.elastic.co/blog/improving-response-latency-in-elasticsearch-with-adaptive-replica-selection) |
| ES | Faster "top k" queries | Huge speed boost when retrieving only top k hits of a search query | [blog post](https://www.elastic.co/blog/faster-retrieval-of-top-hits-in-elasticsearch-with-block-max-wand) |
| ES | Function scoring | Script score queries provide a simpler, modular, and more flexible way to generate a ranking score per record | [blog post](https://www.elastic.co/blog/better-than-average-sort-by-best-rating-with-elasticsearch) |
| ES | New ranking | New field types to boost documents based on values that are relevant to the scoring | [blog post](https://www.elastic.co/blog/easier-relevance-tuning-elasticsearch-7-0) |
| ES | Nanosecond precision | Elasticsearch now supports anosecond precision in time fields, which allows high-frequency data collection  |  |
| ES | Helm charts | Elastic now provides helm charts for Elasticsearch and Kibana | [blog post](https://www.elastic.co/blog/alpha-helm-charts-for-elasticsearch-kibana-and-cncf-membership) |
| K | New UI | New navigation, dark mode, recent items, responsive, KQL by default... you'll love it! | [K7 release post](https://www.elastic.co/blog/kibana-7-0-0-released) |

## 6.7

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 26 Mar 2019 | 8.0 release | 26 Sept 2020 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-7-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| K | Uptime UI | Active uptime monitoring of services & apps, based on Heartbeat | [blog post](https://www.elastic.co/blog/elastic-uptime-monitoring-solution-released) |
| K | Maps | Dedicated solution for mapping, querying, and visualizing geospatial data | [blog post](https://www.elastic.co/blog/elastic-maps-beta-released) |
| K | Frozen management | Frozen indices can be managed in ILM and index management |  |
| K | Localization | Localizing Kibana, starting with Chinese |  |

## 6.6

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 29 Jan 2019 | 6.7 release | 29 Jul 2020 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-6-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Auditbeat module | Record host, process, socket & user activity on a host, using ECS | [blog post](https://www.elastic.co/blog/introducing-auditbeat-system-module) |
| B | Netflow input | Filebeat adds a new NetFlow input |  |
| L | Java plugins | Introducing native support for input, filter and output java plugins | [blog post](https://www.elastic.co/blog/previewing-native-support-for-java-plugins-in-logstash) |
| APM | OpenTracing | All agents now have [OpenTracing](https://opentracing.io/) compatible bridges | [blog post](https://www.elastic.co/blog/distributed-tracing-opentracing-and-elastic-apm) |
| APM | APM to Infra | When looking at a trace, you can jump to the host or container metrics and logs. This is Observability! |  |
| ES | Frozen indices | Frozen indices allow for a much higher ratio of disk storage to heap, at the expense of search latency | [blog post](https://www.elastic.co/blog/creating-frozen-indices-with-the-elasticsearch-freeze-index-api) |
| ES | SQL Date Histograms | Added support for date histograms via the SQL API |  |
| ML | Annotations | Create annotations tokeep a record of actions taken, from the Kibana UI |  |
| K | ILM | managing indices lifecycle (hot/warm/cold/delete) from Kibana | [blog post](https://www.elastic.co/blog/implementing-hot-warm-cold-in-elasticsearch-with-index-lifecycle-management) |
| K | CCR UI | Two new interfaces to manage remote clusters and remote replication process |  |
| K | PNG export | Export dashboards as a PNG report |  |
| K | Upgrade to 7.0 | Prepare for an upgrade from Elasticsearch 6.x to Elasticsearch 7.0 |  |
| K | ES cluster | Kibana now allows the definition of multiple Elasticsearch nodes |  |

## 6.5

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 14 Nov 2018 | 6.6 release | 14 May 2020 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-5-0-released), [Video](https://youtu.be/dnmqoD0XP18)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Central management | Enroll, configure, and manage Beats deployments from a central place using either the UI or API | [blog post](https://www.elastic.co/blog/introducing-beats-central-management-in-the-elastic-stack) |
| B | Functionbeat | Functionbeat is a new Beat that deploys as a function in serverless platform, and streams cloud infrastructure data to Elasticsearch | [blog post](https://www.elastic.co/blog/functionbeat-serverless-ingestion-for-elasticsearch) |
| APM | Distributed tracing | Distributed tracing gives an end-to-end trace on a request as it traverses multiple services | [video](https://youtu.be/Bz41KzRCM4g), [blog post](https://www.elastic.co/blog/distributed-tracing-opentracing-and-elastic-apm) |
| APM | Monitoring | APM monitoring lets you track the health of your Elastic APM deployments from the Kibana Monitoring app |  |
| ES | Cross Cluster Replication | Synchronization of indices across clusters | [webinar](https://www.elastic.co/webinars/replicate-elasticsearch-data-with-cross-cluster-replication-ccr), [blog post](https://www.elastic.co/blog/follow-the-leader-an-introduction-to-cross-cluster-replication-in-elasticsearch), [another post](https://www.elastic.co/blog/cross-datacenter-replication-with-elasticsearch-cross-cluster-replication), [doc](https://www.elastic.co/guide/en/elastic-stack-overview/current/xpack-ccr.html) |
| ES | ODBC | Query Elasticsearch using the SQL API and the ODBC driver |  |
| ES | Minimal snapshots | 50% smaller snapshots with source-only (needs reindex though) | [doc](https://www.elastic.co/guide/en/elasticsearch/reference/6.5/modules-snapshots.html#_source_only_repository) |
| ML | Multi-bucket span | Detect anomalies that span multiple buckets and adjust anomaly score accordingly | [blog post](https://www.elastic.co/blog/changes-to-elastic-machine-learning-anomaly-scoring-in-6-5) |
| K | Canvas | Create and share live infographic style presentations of your Elasticsearch data | [getting started](https://www.elastic.co/blog/getting-started-with-canvas-in-kibana), [metrics and markdown](https://www.elastic.co/blog/kibana-canvas-metric-and-markdown-elements), [airport security](https://www.elastic.co/blog/monitoring-airport-security-operations-with-canvas-and-elasticsearch), [bikes sharing](https://www.elastic.co/blog/eye-catching-canvas-dashboards-on-top-of-bike-sharing-data), [tables and debug](https://www.elastic.co/blog/kibana-canvas-data-table-and-debug-elements), [AMA booth](https://www.elastic.co/blog/elasticon-kibana-canvas-story-ama), [coffee machine](https://www.elastic.co/blog/elasticon-kibana-canvas-story-elasticoffee), [demo video](https://youtu.be/fxA5GE1-V50), [preview at Elastic{ON}](https://youtu.be/NhJi-9DkvdI) |
| K | Spaces | Kibana Spaces organize your Kibana objects (for eg. visualizations and dashboards) into separate "spaces", and use RBAC to control which users have access to which space | [intro](https://www.elastic.co/blog/introducing-kibana-spaces-for-organization-and-security), [migration](https://www.elastic.co/blog/how-to-migrate-to-kibana-spaces), [5mn video](https://youtu.be/RUMi5HUsWxM) |
| K | Sample data | Several datasets (with dashboard, canvas, etc) are available to start playing around in Kibana! | [5mn video](https://youtu.be/qg5_k4ogpzY), [another one](https://youtu.be/32NbRQHHAYQ), the [flights dataset](https://youtu.be/hMFWu1NfNMU) and the [e-commerce dataset](https://youtu.be/6_DrY9_bVDY) |
| K | Rollup UI | Management UI to configure and manage and visualize rollup indices (for metrics) | [blog post](https://www.elastic.co/blog/how-to-create-manage-and-visualize-elasticsearch-rollup-data-in-kibana) |
| K | Data visualizer | This new UI (in ML tab) finds the structure of an uploaded file, generates the grok, ingest pipeline and mapping to eventually import data in Elasticsearch | [blog post](https://www.elastic.co/blog/importing-csv-and-log-data-into-elasticsearch-with-file-data-visualizer) and [earthquake data import](https://www.elastic.co/blog/aftershock-therapy-with-elasticsearch-and-csv-data-import) |
| K | Infra UI | The Infrastructure solution allows to easily navigate between logs and metrics activity on any specific host, pod, or container | [blog post](https://www.elastic.co/blog/elastic-infrastructure-app-released), [other post](https://www.elastic.co/blog/infrastructure-and-logs-ui-new-ways-for-ops-to-interact-with-elasticsearch), [6mn video](https://youtu.be/t4Ny-tcMES4), [preview at Elastic{ON}](https://youtu.be/NzHGDyAQ2_Y) |
| K | Logs UI | The Logs UI in Kibana displays live trail, like a `tail -f` combined with a grep | [blog post](https://www.elastic.co/blog/elastic-logs-app-released), [other post](https://www.elastic.co/blog/infrastructure-and-logs-ui-new-ways-for-ops-to-interact-with-elasticsearch) |

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
| APM | Java agent | New APM agent for Java | [blog post](https://www.elastic.co/blog/elastic-apm-java-agent-beta-released), [perf tuning](https://www.elastic.co/blog/performance-tuning-of-the-elastic-apm-java-agent), [plugin contrib](https://www.elastic.co/blog/a-cookbook-for-contributing-a-plugin-to-the-elastic-apm-java-agent), [5mn video](https://youtu.be/mm0sdldjeo0) |
| APM | RUM agent | Real User Monitoring | [blog post](https://www.elastic.co/blog/elastic-apm-rum-js-agent-is-generally-available), [another post](https://www.elastic.co/blog/performing-real-user-monitoring-rum-with-elastic-apm) |
| ES | Kerberos auth | Use Kerberos as authentication realm | [blog post](https://www.elastic.co/blog/how-to-secure-your-elasticsearch-clusters-using-kerberos) |
| ES | FIPS 140-2 | Elasticsearch now has the ability to run with a FIPS 140-2 enabled JVM | [blog post](https://www.elastic.co/blog/configuring-elasticsearch-in-a-fips-140-2-environment) |
| ES | Field alias | Create aliases on fields, no need to reindex anymore. Good to get prepared for [ECS](https://github.com/elastic/ecs) |  |
| ML | Custom rules | Custom rules for fine tuning machine learning results (to avoid learning or alerting on specific conditions) | [blog post](https://www.elastic.co/blog/how-to-capture-domain-knowledge-in-elastic-machine-learning-jobs-with-custom-rules) |

## 6.3

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 13 Jun 2018 | 6.4 release (23 Aug 2018) | 13 Dec 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-3-0-released), [Video](https://youtu.be/q9R7r4ncaPY)

Opening the code of X-Pack: [Webpage](https://www.elastic.co/products/x-pack/open), [Blog post](https://www.elastic.co/blog/doubling-down-on-open) and [Elastic{ON} announcement](https://youtu.be/gR3OhOnCMf8)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | K8S and Docker autodiscovery | The Autodiscover feature allows logs & metrics to be captured automatically | [blog post](https://www.elastic.co/blog/docker-and-kubernetes-hints-based-autodiscover-with-beats), [another one](https://www.elastic.co/blog/monitoring-kubernetes-and-docker-containers-with-beats-logs-metrics-and-metadata), [video](https://youtu.be/1-iUoWGfByE) |
| B | syslog input | Send logs to Filebeat using syslog over UDP or TCP | [blog post](https://www.elastic.co/blog/brewing-in-beats-syslog-input-in-filebeat) |
| L | Connecting pipelines | Multi-staged processing pipelines can connect pipelines within a Logstash process |  |
| APM | Watcher integration | Receive alerts on errors (in APM data) |  |
| ES | SQL | Query Elasticsearch using the SQL language, coming with a JDBC driver | [part 1](https://www.elastic.co/blog/an-introduction-to-elasticsearch-sql-with-practical-examples-part-1) and [part 2](https://www.elastic.co/blog/an-introduction-to-elasticsearch-sql-with-practical-examples-part-2) |
| ES | Rollups | Take historic data and generate aggregate statistics. Very useful for metrics in particular | [video](https://youtu.be/I5-9x_pQ-Y0) |
| ML | CCS support | Machine Learning jobs now support Cross Cluster Search |  |
| K | Auto complete | Auto complete added in the Kibana Discover query bar | [blog post](https://www.elastic.co/blog/improving-kibanas-query-language) |
| K | Index Management UI | Browse indices, see details about an individual, and change some options (close, force merge, clear cache, etc.) directly from the UI |  |

## 6.2

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 6 Feb 2018 | 6.3 release (13 Jun 2018) | 6 Aug 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-2-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Monitoring | Monitor Beats health in a new Kibana UI |  |
| B | Keystore | Hide passwords from configuration files using a secure keystore | [blog post](https://www.elastic.co/blog/brewing-in-beats-password-keystore) |
| L | Keystore | Hide passwords from configuration files using a secure keystore |  |
| L | JDBC static filter |  |  |
| ES | Rank Evaluation | Track how rankings of expected results is measured against specific queries | [blog post](https://www.elastic.co/blog/made-to-measure-how-to-use-the-ranking-evaluation-api-in-elasticsearch) |
| ES | SAML support | Get access to the Elastic Stack with the introduction of SAML support | [blog post](https://www.elastic.co/blog/how-to-enable-saml-authentication-in-kibana-and-elasticsearch), [SAML on Azure](https://www.elastic.co/blog/saml-based-single-sign-on-with-elasticsearch-and-azure-active-directory) |
| ML | Calendar setting | Skip analyzing the data during scheduled events (entered manually or imported via ics) |  |
| K | Vega | Support for Vega & Vega lite visualizations | [getting started](https://www.elastic.co/blog/getting-started-with-vega-visualizations-in-kibana), [blog post](https://www.elastic.co/blog/custom-vega-visualizations-in-kibana), [sankey viz](https://www.elastic.co/blog/sankey-visualization-with-vega-in-kibana) |

## 6.1

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 13 Dec 2017 | 6.2 release (6 Feb 2018) | 13 Jun 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-1-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | TLS support | Packetbeat adds support for the TLS protocol to inspect the TLS enveloppe |  |
| L | Ruby filter | Complex modification of events in Logstash is now possible via the Logstash Ruby filter |  |
| APM | New! | APM released, with server, agents and UI | [blog post](https://www.elastic.co/blog/elastic-apm-beta-released), [python agent](https://www.elastic.co/blog/creating-custom-framework-integrations-with-the-elastic-apm-python-agent) |
| ES | Split API | Each original primary shard is split into two, or more, primary shards in the new index, as a companion to the Shrink Index API |  |
| ES | Composite agg | The composite aggregation is designed to return all terms and sorted in 'natural order' | [blog post](https://www.elastic.co/blog/composite-aggregations-elasticsearch-pizza-delivery-metrics) |
| ML | Forecasting | Based on the past, what values would you expect in the future | [blog post](https://www.elastic.co/blog/elasticsearch-machine-learning-on-demand-forecasting), [video](https://youtu.be/wJVgh5knV4E) |
| K | Input control | Input control visualization components allow users to select particular values and guide to important filtering values for a dashboard | [blog post](https://www.elastic.co/blog/interactive-inputs-on-kibana-dashboards), [video](https://youtu.be/W1w76rysykI) |

## 6.0

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 14 Nov 2017 | 6.1 release (13 Dec 2017) | 14 May 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-6-0-0-released), [Video (FR)](https://youtu.be/mL-2Uorq9-k)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Docker & K8S | Logs and metrics out of Kubernetes and Docker | [docker](https://www.elastic.co/blog/enrich-docker-logs-with-filebeat), [kubernetes](https://www.elastic.co/blog/shipping-kubernetes-logs-to-elasticsearch-with-filebeat), [5mn video](https://youtu.be/4E3-k0eFcj0) |
| B | Auditbeat | A new beat to capture auditd (based on the Linux audit framework) | [blog post](https://www.elastic.co/blog/introducing-auditbeat-ship-linux-audit-logs-to-elasticsearch) |
| L | Multiple pipelines | Run multiple pipelines concurrently for different use cases in the same instance, with centralized pipeline management, pipeline viewer and a conversion tool from ingest pipelines! | [blog post](https://www.elastic.co/blog/logstash-multiple-pipelines), [management UI](https://www.elastic.co/blog/logstash-centralized-pipeline-management), [pipeline viewer](https://www.elastic.co/blog/logstash-pipeline-viewer-6-0) and [conversion tool](https://www.elastic.co/blog/ingest-node-to-logstash-configuration-converter), [doc](https://www.elastic.co/guide/en/logstash/6.0/multiple-pipelines.html) |
| ES | Rolling upgrade | Upgrade a cluster without a cluster restart (from 5.6.3 to 6.x) |  |
| ES | Faster restart | Faster Restarts and Recoveries using operations-based shard recovery (using sequence IDs) | [blog post](https://www.elastic.co/blog/elasticsearch-sequence-ids-6-0) |
| ES | Sparse data | sparse fields (with no data) in doc-values will be significantly smaller | [blog post](https://www.elastic.co/blog/minimize-index-storage-size-elasticsearch-6-0) |
| ES | Distributed alerting | Distributed watch execution moves watch execution to the nodes that hold the shards of the watcher index | [Blog post](https://www.elastic.co/blog/distributed-watch-execution-elasticsearch-6.0) |
| ES | Removal of types | Indices now have only a single mapping type | [blog post](https://www.elastic.co/blog/removal-of-mapping-types-elasticsearch), [another](https://www.elastic.co/blog/kibana-6-removal-of-mapping-types), [doc](https://www.elastic.co/guide/en/elasticsearch/reference/6.0/removal-of-types.html) |
| ES | Security | We no longer use `changeme` as a default password! And TLS/SSL between nodes is required when security is enabled | [blog post](https://www.elastic.co/blog/default-security-for-elasticsearch-and-the-elastic-stack), [another](https://www.elastic.co/blog/default-password-removal-elasticsearch-and-x-pack-6-0), [TLS](https://www.elastic.co/blog/tls-elastic-stack-elasticsearch-kibana-logstash-filebeat) | 
| K | Kuery Language | Try out the new Kibana Query Language | [blog post](https://www.elastic.co/blog/building-a-better-search-experience-in-kibana) |
| K | CSV export | Search in Discovery then export matching documents as a CSV file via the reporting menu | [video](https://youtu.be/Jd8-A3fIGjo) |
| K | Watcher UI | New UI for creating and editing alerts based on thresholds | [blog post](https://www.elastic.co/blog/creating-a-threshold-alert-in-elasticsearch-is-simpler-than-ever) |
| K | Full screen & dashboard only | Enter full screen mode when viewing a dashboard and only share dashboards to users | [blog post](https://www.elastic.co/blog/kibana-dashboard-only-mode), [video](https://youtu.be/lZoSL1usU_Y) |
| K | Cluster Alerts | Alerts on Monitoring Email Notifications and License Expiration |  |

## 5.6

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 11 Sep 2017 | 7.0 release | 11 Mar 2019 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-6-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| L | Modules | Logstash modules enable easy setup of Logstash configuration, index mapping in Elasticsearch & Kibana dashboards. Starting with two modules for Netflow and Arcsight  | [Arcsight module](https://www.elastic.co/blog/integrating-elasticsearch-with-arcsight-siem-part-1), [doc](https://www.elastic.co/guide/en/logstash/5.6/logstash-modules.html) |
| ES | Rolling upgrade | Upgrade a cluster without a cluster restart (starting from 5.6.3) |  |
| ES | Java High-level client | New Java high-level REST client (built on top of the low-level client) accepts objects for the most important APIs | [blog post](https://www.elastic.co/blog/the-elasticsearch-java-high-level-rest-client-is-out) |
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
| K | Regions in maps | The Elastic Maps Service now supports region maps | [blog post](https://www.elastic.co/blog/visualizing-france-salary-data-with-region-maps-in-kibana), [another](https://www.elastic.co/blog/region-maps-gauge-kibana) |
| K | Grok debugger | Debug grok patterns (from Logstash or ingest pipelines) in Kibana | [video](https://youtu.be/SKSqPRwDfns) |
| K | CCS support | Index Patterns can now point to indices from remote clusters using cross cluster search feature |  |


## 5.4

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 4 May 2017 | 5.5 release (6 Jul 2017) | 4 Nov 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-4-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Modules | Modules for JMX (using Jolokia) to monitor Java applications, Linux auditd and system authentication logs | [blog post](https://www.elastic.co/blog/monitoring-java-applications-with-metricbeat-and-jolokia) |
| ML | New! | Machine Learning makes it easy to detect anomalies (spot infrastructure problems, cyber attacks, or business issues) by automatically modeling the normal behavior of time series data | [blog post](https://www.elastic.co/blog/introducing-machine-learning-for-the-elastic-stack), [scoring](https://www.elastic.co/blog/machine-learning-anomaly-scoring-elasticsearch-how-it-works), [span](https://www.elastic.co/blog/explaining-the-bucket-span-in-machine-learning-for-elasticsearch), [sizing](https://www.elastic.co/blog/sizing-machine-learning-with-elasticsearch) |
| K | Time Series Visual Builder | Time Series Visual Builder (TSVB) combines pipeline aggregations and a new UI for interacting with, and designing visualizations from, time series data | [getting started](https://www.elastic.co/blog/master-time-with-kibanas-new-time-series-visual-builder), [annotations](https://www.elastic.co/blog/time-series-annotations-and-anomalies-with-kibana), [demo](https://www.elastic.co/elasticon/conf/2017/sf/kibana-visualizations-deep-dive), [video part1](https://youtu.be/CNR-4kZ6v_E), [video part2](https://youtu.be/CvorsH3x7Z8), [video part3](https://youtu.be/xkluflzhpAw) |
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
| ES | CCS | Cross-cluster search, aka searching across multiple clusters, replacing the tribe node | [blog post](https://www.elastic.co/blog/tribe-nodes-and-cross-cluster-search-the-future-of-federated-search-in-elasticsearch) |


## 5.2

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 31 Jan 2017 | 5.3 release (28 Mar 2017) | 31 Jul 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-2-0-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Heartbeat | Heartbeat periodically checks the status of services (availability and round-trip-time) | [blog post](https://www.elastic.co/blog/uptime-monitoring-with-heartbeat-and-the-elastic-stack) |
| B | Prometheus exporter | Prometheus module that collects metrics from the Prometheus exporters |  |
| K | LS Monitoring UI | New monitoring UI with nice graphs and historical data to track changes in your production Logstash instances |  [blog post](https://www.elastic.co/blog/monitoring-logstash-filters), [video](https://youtu.be/Ahfymloitjk) |
| K | Heatmaps | Heatmaps are great to pick out an area of high or low volume in time series data | [blog post](https://www.elastic.co/blog/awesome-new-kibana-visualizations-heatmap-and-point-series) |

## 5.1

| Release date | [End of Maintenance](https://www.elastic.co/support/eol) | [End of Life](https://www.elastic.co/support/eol) |
| --- | --- | --- |
| 8 Dec 2016 | 5.2 release (31 Jan 2017) | 8 Jun 2018 |

Version-level references: [Blog post](https://www.elastic.co/blog/elastic-stack-5-1-1-released)

| Product | Feature | Description | References |
| --- | --- | --- | --- |
| B | Docker module | Periodically collect container metrics from cgroup | [blog post](https://www.elastic.co/blog/monitoring_container_resource_usage_with_metricbeat), [metadata enrichment](https://www.elastic.co/blog/brewing-in-beats-enrich-events-with-docker-metadata) |
| B | Kafka module | Connects to the local Kafka node and reads periodically details about the partitions |  |
| L | Presistent queues | Inbuilt persistent queues enable Logstash to persist events before processing them | [blog post](https://www.elastic.co/blog/logstash-persistent-queue) |
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
| ES | Ingest node | Ingest Node is an Elasticsearch node type enabling some data enrichment capabilities at index time | [blog post](https://www.elastic.co/blog/new-way-to-ingest-part-1), [CSV ingest](https://www.elastic.co/blog/indexing-csv-elasticsearch-ingest-node) |
| ES | Painless scripting | New scripting language for query, alert, reindex, or in an ingest node for a powerful way to manipulate documents | [blog post](https://www.elastic.co/blog/painless-a-new-scripting-language), [video](https://youtu.be/3FLEJJ8PsM4) |
| ES | Keyword field | Analyzed and not-analysed string fields have been replaced by dedicated `text` fields for full text search, and `keyword` fields for string identifier search, sorting, and aggregations |  |
| ES | Shrink API | Shrink an existing index into a new index with fewer primary shards |  |
| ES | Rollover API | Rolls an alias over to a new index when too large or too old | [blog post](https://www.elastic.co/blog/managing-time-based-indices-efficiently) |
| ES | Java Low-level client | A simple low-level Java HTTP/REST client |  |
| ES | Benchmarking | We open sourced our Elasticsearch benchmarking tool Rally | [doc](https://github.com/elastic/rally) |
| K | Timelion | New visualization tool with query DSL and interesting math functions and rendering capabilities | [getting started](https://www.elastic.co/blog/timelion-tutorial-from-zero-to-hero), [blog post](https://www.elastic.co/blog/sparse-timeseries-and-timelion), [another](https://www.elastic.co/blog/mining-earthquake-data-with-kibana-5-and-timelion), [video](https://youtu.be/cfTehOJScL4) |
| K | Console | Build free-form requests to Elasticsearch from Kibana (replacing Sense) |  |
| K | Security UI | Management UI in Kibana for creating and managing both users and roles |  |
| K | Kibana monitoring | Monitoring for Kibana as part of the monitoring (Marvel) UI |  |
| K | Scripted fields | Create computed scripted fields in Kibana using Painless | [video](https://youtu.be/BhmpDtS7g28) |

## Authors

* **Vincent Maury** - *Initial commit* - [blookot](https://github.com/blookot)

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE.md](LICENSE.md) file for details
