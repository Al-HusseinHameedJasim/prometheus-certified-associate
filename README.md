# Prometheus Certified Associate (PCA)
<img src="https://training.linuxfoundation.org/wp-content/uploads/2022/04/Training_Badge_Prometheus_V2-2-300x300.png" width="100">

Curriculum-based resources for the Prometheus Certified Associate (PCA) exam.

According to [The Linux Foundation](https://training.linuxfoundation.org/certification/prometheus-certified-associate/):
> The Prometheus Certified Associate (PCA) exam demonstrates an engineers foundational knowledge of observability and skills using Prometheus, the open source systems monitoring and alerting toolkit.

## Domains & Competencies
The Prometheus Certified Associate (PCA) exam curriculum can be found [here](https://github.com/cncf/curriculum/blob/master/PCA_Curriculum.pdf).

### 📋 Observability Concepts 18%

#### &nbsp; &nbsp; &nbsp; [Metrics](https://prometheus.io/docs/introduction/overview/#what-are-metrics)
#### &nbsp; &nbsp; &nbsp; [Understand logs and events](https://www.honeycomb.io/blog/how-are-structured-logs-different-from-events)
#### &nbsp; &nbsp; &nbsp; [Tracing and Spans](https://docs.splunk.com/Observability/apm/apm-spans-traces/traces-spans.html#:~:text=What%20are%20traces%20and%20spans,single%20operation%20within%20a%20trace.)
#### &nbsp; &nbsp; &nbsp; [Push vs Pull](https://prometheus.io/docs/introduction/faq/#why-do-you-pull-rather-than-push)
#### &nbsp; &nbsp; &nbsp; [Service Discovery](https://www.youtube.com/watch?v=PzFUwBflXYc&t=339s)
#### &nbsp; &nbsp; &nbsp; [Basics of SLOs, SLAs, and SLIs](https://cloud.google.com/blog/products/devops-sre/sre-fundamentals-slis-slas-and-slos)

### 📋 Prometheus Fundamentals 20%

#### &nbsp; &nbsp; &nbsp; [System Architecture](https://prometheus.io/docs/introduction/overview/#architecture)
#### &nbsp; &nbsp; &nbsp; [Configuration](https://prometheus.io/docs/prometheus/latest/configuration/configuration) and [Scraping](https://www.oreilly.com/library/view/prometheus-up/9781492034131/ch01.html#idm45497381503248)
#### &nbsp; &nbsp; &nbsp; [Understanding Prometheus Limitations](https://youtu.be/m0JgWlTc60Q?t=282)
#### &nbsp; &nbsp; &nbsp; [Data Model and Labels](https://prometheus.io/docs/concepts/data_model)
#### &nbsp; &nbsp; &nbsp; [Exposition Format](https://prometheus.io/docs/instrumenting/exposition_formats/#exposition-formats)

### 📋 PromQL 28%
  
#### &nbsp; &nbsp; &nbsp; [Selecting Data](https://promlabs.com/blog/2020/07/02/selecting-data-in-promql)
#### &nbsp; &nbsp; &nbsp; [Rates](https://prometheus.io/docs/prometheus/latest/querying/functions/#rate) and [Derivatives](https://prometheus.io/docs/prometheus/latest/querying/functions/#deriv)
#### &nbsp; &nbsp; &nbsp; [Aggregating over time](https://prometheus.io/docs/prometheus/latest/querying/functions/#aggregation_over_time)
#### &nbsp; &nbsp; &nbsp; [Aggregating over dimensions](https://prometheus.io/docs/prometheus/latest/querying/operators/#aggregation-operators)
#### &nbsp; &nbsp; &nbsp; [Binary operators](https://prometheus.io/docs/prometheus/latest/querying/operators/#binary-operators)
#### &nbsp; &nbsp; &nbsp; [Histograms](https://prometheus.io/docs/practices/histograms)
#### &nbsp; &nbsp; &nbsp; [Timestamp Metrics](https://prometheus.io/docs/prometheus/latest/querying/functions/#timestamp)

### 📋 Instrumentation and Exporters 16%
  
#### &nbsp; &nbsp; &nbsp; [Client Libraries](https://prometheus.io/docs/instrumenting/clientlibs/#client-libraries)
#### &nbsp; &nbsp; &nbsp; [Instrumentation](https://prometheus.io/docs/practices/instrumentation)
#### &nbsp; &nbsp; &nbsp; [Exporters](https://prometheus.io/docs/instrumenting/exporters)
#### &nbsp; &nbsp; &nbsp; [Structuring and naming metrics](https://prometheus.io/docs/practices/naming/#metric-names)

### 📋 Alerting & Dashboarding 18%
  
#### &nbsp; &nbsp; &nbsp; [Dashboarding basics](https://www.oreilly.com/library/view/prometheus-up/9781492034131/ch06.html#grafana_chapter)
#### &nbsp; &nbsp; &nbsp; [Configuring Alerting rules](https://prometheus.io/docs/prometheus/latest/configuration/alerting_rules/#:~:text=Alerting%20rules%20are%20configured%20in,same%20way%20as%20recording%20rules.&text=The%20optional%20for%20clause%20causes,as%20firing%20for%20this%20element.)
#### &nbsp; &nbsp; &nbsp; [Understand and Use Alertmanager](https://prometheus.io/docs/alerting/latest/alertmanager/#alertmanager)
#### &nbsp; &nbsp; &nbsp; [Alerting basics (when, what, and why)](https://prometheus.io/docs/practices/alerting/#alerting)
