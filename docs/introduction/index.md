# Otel Workshop Introduction  

- The Splunk OpenTelemetry Workshop will teach you how to level up your Observability practice by using the OpenTelemetry Collector and APM Instrumentation to emit industry standard telemetry from your infrastructure and applications.
- This workshop is designed to run as a single user, or be run in a small group (upwards of 6) along with a leader guiding the group.
    - If running as a group, a pre-workshop prep call is necessary to ensure that all group members can spin up and/or access an Ubuntu Linux lab environment. Details are below.

## Details  

- Audience: Intermediate and advanced developers, devops, and SREs who have already set up their Splunk Observability Cloud account and have tried out integrations and dashboards Skill level should include setting up and troubleshooting Linux and Kubernetes environments as well as deploying applications written in current versions of Java, Python, Node.
- APM: monitors self written apps, with a focus on microservices, using current frameworks i.e. Java >=8, Python >= 3.6
- All examples have source code supplied

## Requirements  

- Prerequisites: completion of [Splunk Observability Workshop](https://signalfx.github.io/observability-workshop/latest/) which trains on using metrics/APM and charts/dashboards/alerts or equivalent devops/SRE skills
- Splunk Observability Cloud Account
- Ability to spin up a VM or access a host with a Debian Linux environment with the following specs:
    - Debian (i.e. Ubuntu) Linux environment with minimum 12G RAM and 20G disk w/ lightweight Kubernetes (Rancher k3s) installed OR your own k8s cluster

## Workshop Agenda  

- (Optional) Build a local Lab Environment Ubuntu Sandbox on Mac or Windows
- OpenTelemetry Collector and APM Labs
    - Linux Host
        - Set up OpenTelemetry Collector Agent on a Linux Host
        - OpenTelemetry APM Instrumentation on Java, Python, and Node apps
    - Kubernetes (k8s) [Click to start at k8s labs](../apm/k8s)
        - Set up OpenTelemetry Collector Agent on a k8s cluster
        - OpenTelemetry APM Instrumentation on k8s on Java, Python k8s pods
        - Manual APM Instrumentation for Java
        - JVM Metrics
        - Span processing with redaction example
        - APM for Istio service mesh
        - OpenTelemetry Collector configuration / troubleshooting
          - Prometheus scraping and custom metrics
          - Collectd: receive metrics from any platform
          - Troubleshooting the Collector

## Disclaimers

- This is not product documentation. Official documentation: https://docs.splunk.com/Observability
- These examples are unsupported and are for experimentation and educational purposes only