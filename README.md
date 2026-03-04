# Hey, I'm Kris

SRE and infrastructure engineer based in Twin Falls, Idaho. I spent eight years in the Marine Corps as a network and systems administrator before moving into the private sector — I've been building, breaking, and fixing infrastructure ever since.

I care about reliability, observability, and automation that actually gets used. Most of my work lives in AWS, Linux, and Python, with a heavy dose of "why did we not know about this sooner" driving the monitoring side of things.

Outside of work I run a self-hosted homelab for my family, occasionally help small local businesses with their technology needs, and build things that don't always need a good reason to exist.

---

## What I Work With

<p>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white" />
</p>

---

## Client Work
**[event-business-platform](https://github.com/yourusername/event-business-platform)** — Serverless AWS platform built for a real event planning client. Lambda, API Gateway, DynamoDB, Stripe, and OpenPhone — production since 2024. Architecture and design decisions documented; source omitted to protect client information.

---

## Personal Projects
**[homelab](https://github.com/yourusername/homelab)** — Self-hosted family infrastructure running on Docker with full monitoring, a 3-2-1-1-0 backup strategy, and zero services exposed to the internet. Prometheus, Grafana, Node Exporter, SNMP for the NAS, Blackbox for connectivity — all dashboards built from scratch.

---

## Things I've Built
**PB-scale archival migration** — Designed and built a distributed Python system to move over a petabyte of data off a NetApp into S3 Glacier Deep Archive. V1 used SQLite for state tracking; V2 replaced it with PostgreSQL to coordinate 8 parallel VMs each running dedicated threads for indexing, compression, and upload — sharding the dataset by hash to prevent overlap. Built the restore tooling alongside it. A backup you can't restore isn't a backup.

**Custom SAP Business One / HANA backup solution** — Designed and implemented a full backup system for a business-critical HANA environment: transaction log backups and data backups stored locally, replicated to S3, and cross-region replicated to a second S3 bucket. GFS retention keeps storage costs manageable. Full monitoring and alerting integrated into LogicMonitor with custom datasources.

---

## Certifications
`VMware VCP-DCV` &nbsp;|&nbsp; `AWS Cloud Practitioner` &nbsp;|&nbsp; `CompTIA Security+` &nbsp;|&nbsp; `Cisco CCNA` &nbsp;|&nbsp; `CompTIA A+` &nbsp;|&nbsp; `LPI Linux Essentials`

---

## Contact
📧 KDScheuer97@gmail.com &nbsp;|&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/kdscheuer/)
