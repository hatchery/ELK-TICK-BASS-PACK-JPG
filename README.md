# ELK-TICK-BASS-PACK-JPG
Logging Pipeline and Chief.
This is a joke, but totally serious.

- E - Elasticsearch
    * A full-text search-oriented data store. To be used for searching log files and maintaining a working-set of logs.
- L - Logstash
    * A structured log collection daemon. For groking, parsing and injesting log files.
- K - Kibana
    * A data visualization and discovery system for elasticsearch.

---

- T - Telegraf
    * A light weight data collection instrument for injesting metrics and logs.
- I - InfluxDB
    * A time series database for storing and measuring historic metrics.
- C - Chronograf
    * A query creation and data discovery system for InfluxDB.
- K - Kapacitor
    * An anomaly detection system for InfluxDB.

---

- B - Beats
    * Lightweight data shippers for metrics and log files.
- A - auth proxy
    * A proxy in front of some of the HTTP-driven utilities to give them authorization.
    This is a generic piece which can be filled by Keycloak or oauth2_proxy or nginx.
- S - StatsD
    * A metrics reciever and standard exporting format.
    This is a generic piece which can be filled by StatsD, statsite, go-statsd or a number of other servers.
- S - Sentry
    * An exception monitoring and ticketing system for globally recognizing errors and exceptions within your application.

---

- P - PushGateway
    * A prometheus injestion service for clients who implement the prometheus metric format but are short-lived and need a place to export.
- A - AlertManager
    * A prometheus alerting system and anomaly detection system.
- C - CollectD
    * A dynamic metrics and log exfiltration daemon to cover any places which beats and telegraf do not export well.
- K - Kafka
    * A distributed message queue for scaling log injestion across a number of interconnected systems to reduce the external call traffic of your servers.

--

- J - Jaeger
    * A distributed tracing visualizer, adhering to the opentracing standard.
- P - Prometheus
    * A poll-based metrics query engine, visualizer and toolkit for quickly monitoring systems
- G - Grafana
    * A full-featured dashboarding and querying system for all of the data backends.

Clearly a system for collecting all data in all ways and keeping it forever and ever.
