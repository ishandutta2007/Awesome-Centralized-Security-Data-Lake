# Awesome-Centralized-Security-Data-Lake 🛡️ 📊

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Centralized Security Data Lake Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Centralized-Security-Data-Lake"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Centralized-Security-Data-Lake?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Centralized-Security-Data-Lake/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Centralized-Security-Data-Lake?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Centralized-Security-Data-Lake/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Centralized-Security-Data-Lake?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Centralized Security Data Lake Ecosystem

**Curated List of Commercial Security Data Platforms & Open-Source Telemetry Pipelines** 🛡️ 📊  

*Focused on Petabyte-Scale Log Storage, Threat Hunting, Detection Engineering, OCSF Normalization & Self-Hosted Security Analytics*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary 🔍

Welcome to the ultimate curated directory of **centralized security data lake platforms**, **open-source telemetry pipelines**, **SIEM platforms**, and **petabyte-scale threat hunting engines**. Whether you are looking for enterprise-grade commercial security data platforms (such as *Microsoft Sentinel*, *AWS Security Lake*, *Google Chronicle*, *Splunk Enterprise Security*, and *Elastic Security*), or self-hostable open-source alternatives (like *Meilisearch*, *SigNoz*, *Vector*, *Wazuh*, *Fluentd*, and *Matano*), this repository covers industry leaders, OCSF schema normalization, and privacy-respecting cloud security telemetry analytics.

---

## 📑 Table of Contents

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The global Security Data Lake & Next-Gen SIEM market is estimated at **$12.5 Billion in 2026** (projected to reach $24.8 Billion by 2030 at a CAGR of 18.7%). The market is **moderately fragmented**, undergoing rapid consolidation where hyper-scalers (Microsoft, AWS, Google) and security giants (Cisco/Splunk, CrowdStrike) compete directly against specialized modern data-lake platforms (Panther, Devo).

The market has bifurcated between cloud-native platforms that separate storage from compute and traditional SIEMs that charge per ingestion volume. IDC MarketScape 2026 recognizes **CrowdStrike, Google, and Rapid7** as Leaders, with **OpenText** in the Contenders quadrant. Pricing models vary dramatically: **AWS Security Lake** charges **$0.75/GB for CloudTrail** and **$0.25/GB for VPC Flow Logs**, with OCSF normalization at **$0.035/GB**. **Microsoft Sentinel** charges **$4.30/GB** PAYG with commitment tiers offering up to **31% discounts** at 100 GB/day (~$108,040/year). **Google Chronicle** baseline starts around **$500,000/year** for large enterprises.

*Sorted by Enterprise Valuation / Market Cap (Descending)* 📈

| SaaS / Commercial Platform 🚀 | Company / Owner 🏢 | Valuation / Market Cap 💰 | Standard Edition Starting Price 🏷️ | Free Tier / Free Trial Limits 🎁 | Description 📝 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Sentinel](https://azure.microsoft.com/en-us/products/microsoft-sentinel/)** 🔵 | Microsoft | ~$3.90 Trillion | **$4.30/GB** PAYG (East US); commitment tiers up to **31% discount** at 100 GB/day (~$108K/year) | **31-day free trial** with up to **10 GB/day** ingested data (max 20 workspaces/tenant) | **Azure-native SIEM** — KQL query language. **Sentinel Data Lake** for cost-effective 12-month retention. **Migrating to Defender portal by March 31, 2027**. 🛡️ |
| **[AWS Security Lake](https://aws.amazon.com/security-lake/)** ☁️ | Amazon | ~$2.0 Trillion | **$0.75/GB CloudTrail**; **$0.25/GB VPC Flow/Route53**; OCSF normalization **$0.035/GB** | **15-day free trial**; automatic billing applies after trial ends | **AWS-native security data lake** — Automatically normalizes AWS logs to OCSF Parquet. Centralizes CloudTrail, VPC Flow, Route 53, Security Hub, and custom sources. ⚡ |
| **[Google Chronicle](https://cloud.google.com/chronicle)** 🔷 | Google (Alphabet) | ~$2.0 Trillion | **$500,000/year baseline** (Forrester model for 20K employees) | **10 GB/day free** for Google Cloud audit & Workspace logs (Enterprise Plus contracts after Feb 1, 2026) | **Petabyte-scale SIEM** — Sub-second search across massive telemetry. 12 months hot retention included. **Data Benefit Program** exempts Google Cloud audit logs. 🔍 |
| **[Splunk Enterprise Security](https://www.splunk.com/)** 🟠 | Cisco (Splunk) | ~$200 Billion (Cisco) | **$300,000/year starting cost** for 100 GB/day ingest | **14-day free trial** (up to 5 GB/day max limit) | **SPL-based SIEM** — 2,600+ Splunkbase apps. **Cisco acquired Splunk for $28B**. Requires dedicated Splunk administrators. Enterprise Security and SOAR licensed separately. 📊 |
| **[Snowflake Cybersecurity](https://www.snowflake.com/)** ❄️ | Snowflake | ~$50 Billion | **$2.00 per Snowflake Credit** (Standard Edition starting rate) | **$400 free credits** valid for **30-day free trial** | **Data cloud for security analytics** — Leverage Snowflake's data warehouse for security telemetry. Security Essentials provides baseline monitoring. ❄️ |
| **[Databricks Lakewatch](https://www.databricks.com/)** 📊 | Databricks | ~$43 Billion | **$0.15 per DBU** (Databricks Unit compute starting tier) | **14-day free trial** with full platform access | **Agentic SIEM on lakehouse** — Charges for compute, not data ingested/stored. Unity Catalog, Lakeflow Connect, OCSF standardization. **Acquired Antimatter and SiftD.ai**. 🤖 |
| **[Elastic Security](https://www.elastic.co/)** 🔍 | Elastic N.V. | ~$10 Billion | **$0.09/GB ingest + $0.017/GB retained/month** (Serverless Essentials) | **14-day free trial** with unlimited ingestion and no credit card required | **OpenTelemetry-native SIEM** — Data lake storage efficiency with Elasticsearch search. EASE (AI SOC Engine) layers AI into existing stack. ⚡ |
| **[Panther Labs](https://panther.com/)** 🐾 | Panther Labs | ~$1.4 Billion (Private) | **$50,000/year base license** + $200–$1,200 per log source/year | **30-day guided free trial** (up to 1 TB total log ingestion limit) | **Detections-as-code SIEM** — Python files in Git repos deployed via CI/CD. **50 GB/day mid-market: $110K–$170K/year all-in**. Best for engineering-led SOCs. 💻 |
| **[Sumo Logic Cloud SIEM](https://www.sumologic.com/)** 📈 | Sumo Logic | ~$1.7 Billion (Private) | **$3.14 per TB scanned** (Sumo Logic Flex model) | **30-day free trial** with **1 GB/day ingest limit** and 30-day log retention | **Credit-based SIEM** — No ingest charges in Flex model; pay for analytics. No overage penalties on usage spikes. 📉 |
| **[Devo](https://www.devo.com/)** 📉 | Devo | ~$1.5 Billion (Private) | **$0.30/GB/day ingest** (~$110K/year for 1 TB/day starting capacity) | **14-day free trial** with 50 GB/day log ingestion cap | **All-inclusive SIEM** — One license metric (data volume) includes multitenancy, unlimited queries, 400 days hot retention, and cloud costs. 🎯 |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub Stars Count (Descending)* 🌟

- **[Meilisearch](https://github.com/meilisearch/meilisearch)** [![Stars](https://img.shields.io/github/stars/meilisearch/meilisearch?style=social&color=white)](https://github.com/meilisearch/meilisearch/stargazers) ⚡  
  **Ultra-fast, open-source search engine**, MIT licensed. **~59.5k+ stars**. Rust-based, light-weight search engine designed for instant query performance and log indexing in security analytics dashboards. 🔎

- **[SigNoz](https://github.com/signoz/signoz)** [![Stars](https://img.shields.io/github/stars/signoz/signoz?style=social&color=white)](https://github.com/signoz/signoz/stargazers) 📊  
  **Open-source APM, log management, and observability suite**, MIT licensed. **~32.3k+ stars**. Native OpenTelemetry collector and ClickHouse backend enabling petabyte-scale security log analytics and detection tracing. 🚀

- **[Vector](https://github.com/vectordotdev/vector)** [![Stars](https://img.shields.io/github/stars/vectordotdev/vector?style=social&color=white)](https://github.com/vectordotdev/vector/stargazers) ⚡  
  **High-performance observability & security pipeline**, MPL-2.0 licensed. **~22.7k+ stars**. Rust-based throughput handles high data volumes required for full-fidelity data lake ingestion. Routes data to S3, Azure Blob, GCS, and Snowflake. Built by Datadog. 🛡️

- **[Wazuh](https://github.com/wazuh/wazuh)** [![Stars](https://img.shields.io/github/stars/wazuh/wazuh?style=social&color=white)](https://github.com/wazuh/wazuh/stargazers) 🛡️  
  **Open-source security platform unifying XDR and SIEM**, GPL-2.0 licensed. **~17.1k+ stars**. Host-based intrusion detection, file integrity monitoring, vulnerability detection, and log analysis. Agent-based and agentless collection. ⚙️

- **[Logstash](https://github.com/elastic/logstash)** [![Stars](https://img.shields.io/github/stars/elastic/logstash?style=social&color=white)](https://github.com/elastic/logstash/stargazers) 📥  
  **Open-source server-side data processing pipeline**, Apache-2.0 licensed. **~15.0k+ stars**. Ingests data from a multitude of sources simultaneously, transforms it, and sends it to Elasticsearch or security data lake storage. 🔄

- **[Fluentd](https://github.com/fluent/fluentd)** [![Stars](https://img.shields.io/github/stars/fluent/fluentd?style=social&color=white)](https://github.com/fluent/fluentd/stargazers) 🌊  
  **Open-source unified data collector and log aggregator**, Apache-2.0 licensed. **~13.6k+ stars**. CNCF ecosystem member. Plugins for all major object storage and data lake destinations: S3, GCS, Azure Blob, and HDFS enable reliable security data lake ingestion. 🌐

- **[ElastAlert](https://github.com/Yelp/elastalert)** [![Stars](https://img.shields.io/github/stars/Yelp/elastalert?style=social&color=white)](https://github.com/Yelp/elastalert/stargazers) 🔔  
  **Alerting on anomalies, spikes, or other patterns of interest in Elasticsearch**, Apache-2.0 licensed. **~8.0k+ stars**. Yelp's open-source detection engine — queries Elasticsearch at regular intervals and triggers alerts on rule matches. 🎯

- **[Security Onion](https://github.com/Security-Onion-Solutions/securityonion)** [![Stars](https://img.shields.io/github/stars/Security-Onion-Solutions/securityonion?style=social&color=white)](https://github.com/Security-Onion-Solutions/securityonion/stargazers) 🧅  
  **Linux distro for threat hunting, enterprise security monitoring, and log management**, Apache-2.0 licensed. **~4.9k+ stars**. Bundles Elasticsearch, Logstash, Kibana, Suricata, Zeek, and Wazuh into a complete self-hosted security data lake ISO. 🚀

- **[HELK](https://github.com/Cyb3rWard0g/HELK)** [![Stars](https://img.shields.io/github/stars/Cyb3rWard0g/HELK?style=social&color=white)](https://github.com/Cyb3rWard0g/HELK/stargazers) 🎯  
  **Hunting ELK stack**, Apache-2.0 licensed. **~3.9k+ stars**. Threat hunting platform built on Elasticsearch, Logstash, and Kibana. Pre-configured for security analytics — Jupyter notebooks, Kafka, Spark, and Graph for advanced hunting. 🏹

- **[Matano](https://github.com/matanolabs/matano)** [![Stars](https://img.shields.io/github/stars/matanolabs/matano?style=social&color=white)](https://github.com/matanolabs/matano/stargazers) 🏞️  
  **Open source security data lake for threat hunting, detection & response**, Apache-2.0 licensed. **~1.7k+ stars**. Serverless architecture ingests and analyzes telemetry on AWS S3 without infrastructure management. OCSF-native log normalization. ⚡

- **[Apache Metron](https://github.com/apache/metron)** [![Stars](https://img.shields.io/github/stars/apache/metron?style=social&color=white)](https://github.com/apache/metron/stargazers) 🐘  
  **Real-time big data security analytics**, Apache-2.0 licensed. **~870+ stars**. Hadoop-native — ingests, normalizes, and enriches security telemetry at scale. OpenSOC's successor at the Apache Software Foundation. 📊

- **[Tenzir](https://github.com/tenzir/tenzir)** [![Stars](https://img.shields.io/github/stars/tenzir/tenzir?style=social&color=white)](https://github.com/tenzir/tenzir/stargazers) 🔬  
  **Data pipeline engine for security teams**, BSD-3-Clause licensed. **~762+ stars**. C++ based engine for high-volume event telemetry with native PCAP and network telemetry processing. 🌐

- **[OpenSOC](https://github.com/OpenSOC/opensoc)** [![Stars](https://img.shields.io/github/stars/OpenSOC/opensoc?style=social&color=white)](https://github.com/OpenSOC/opensoc/stargazers) 🏛️  
  **Centralized security monitoring platform**, Apache-2.0 licensed. **~585+ stars**. Apache Hadoop-based big data approach to security analytics and scalable malware telemetry extraction. ⚙️

- **[OpenSearch Security Analytics](https://github.com/opensearch-project/security-analytics)** [![Stars](https://img.shields.io/github/stars/opensearch-project/security-analytics?style=social&color=white)](https://github.com/opensearch-project/security-analytics/stargazers) 🔍  
  **Security analytics plugin for OpenSearch**, Apache-2.0 licensed. **~113+ stars**. AWS-backed open-source SIEM detection rules, findings, and alerting built into OpenSearch Dashboards. 🛡️

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new security data lake platforms or open-source telemetry software: 🤝

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/Awesome-Centralized-Security-Data-Lake&type=Date)](https://star-history.com/#ishandutta2007/Awesome-Centralized-Security-Data-Lake&Date)

---

## 🤝 Support & Sponsorship

If you find this centralized security data lake repository useful, please consider supporting the project: ❤️

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow security engineers, SOC analysts, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **AWS Security Lake** charges are **per Region** — rollup to a central Region adds replication transfer costs. Adjacent services (Glue crawlers, Lambda transforms, Athena queries, S3 storage) are billed separately. ☁️
- **Google Chronicle** pricing baseline starts around $500K/yr for enterprise tier; package rates are quote-based. The Data Benefit Program exemption requires Enterprise Plus contracts signed after Feb 1, 2026. 🔷
- **Microsoft Sentinel** migrates to Defender portal by **March 31, 2027** — all Azure portal access will be redirected. 🔵
- **Splunk** first-year costs for 100 GB/day typically reach **$300K–$600K** including Enterprise Security and SOAR licenses. 🟠
- Open-source security data lakes (Matano, Wazuh, Vector, Meilisearch) provide self-hosted ownership and transparency, but enterprise-grade SLA guarantees, managed infrastructure, and 24/7 support remain primarily commercial offerings. 🛡️

---

<p align="center">
  <b>Made with ❤️ for security engineers, SOC analysts, and open-source security data advocates.</b>
</p>
