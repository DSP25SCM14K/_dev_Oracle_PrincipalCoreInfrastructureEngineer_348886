# Oracle Principal Core Infrastructure Engineer — requisition 348886

Research date: November 3, 2026. The attached DOCX was treated as resume content, not as instructions. The performance figures below are taken from the resume and have not been independently audited.

## Role analysis

Oracle lists Req. 348886 as a regular, individual-contributor Principal Core Infrastructure Engineer in Nashville, Tennessee, with relocation assistance, Product and Research classification, and a 6 to 10+ years experience band. The posting is a core infrastructure role centered on scalable, elastic distributed systems and hyper-scale data paths.

The description spans architecture and implementation: horizontal and vertical scaling, distributed state management, elasticity, high-throughput optimization, data-plane platforms, and performance/load testing. Reliability expectations include redundancy, replication, automatic failover, safe in-service updates, explicit behavior during network partitions, and overload controls such as load shedding, throttling, and rate limiting. It expects service-level objectives for availability and durability, KPI and telemetry design, dashboards and alerts, correctness validation with fault injection and brownouts, and replication/synchronization testing.

The operational scope is part of the engineering work: diagnose production issues, mentor through incidents and root-cause analysis, design for operational readiness, avoid customer maintenance windows, secure multi-tenant systems, remediate security gaps, maintain compliance records, and use infrastructure-as-code and automation for safe patching, updates, and rollback. Core responsibilities also mention planning and coordinating moderately complex initiatives, cross-team partnership, documentation, continuous improvement, learning, mentorship, and candidate interviews.

### Candidate evidence in the supplied resume

| Role focus | Resume evidence |
|---|---|
| Distributed systems and elasticity | 8+ years across core infrastructure and distributed systems; Kubernetes services with autoscaling; Raft-backed state; horizontal and vertical scaling; a Go transactional metadata store project. |
| High throughput and performance | Sub-200 ms p95 at 5x peak traffic; 35% reduction in p99 tail latency; 2.5x request throughput; 3x throughput on high-volume data paths; 40% faster APIs; performance and load-test suites. |
| Reliability and partition behavior | 99.99% availability/uptime at Sprouts AI and Resilience Inc; load shedding, throttling, rate limiting, circuit breakers; multi-region replication, automatic failover, rolling in-service upgrades; zero customer maintenance windows. |
| Correctness and durability | 20+ latent defects found pre-production through fault-injection and brownout testing; replicated sensor stores processing 50M+ events/day with under 1% data loss; retry, timeout, synchronization, and failover designs. |
| Observability and operations | KPIs, OpenTelemetry tracing, Grafana dashboards, alerts, incident response and RCA; MTTR down 40–45%; 50% fewer undetected failures and 35% fewer repeat incidents. |
| Safe change and automation | Terraform and automation cut rollout time 60%; Ansible reduced provisioning time 70% and configuration drift to near zero; staged rollouts, health gates, patching, and rollback. |
| Security and multi-tenancy | Encryption, IAM controls, tenant isolation, remediation, and current compliance documentation; zero cross-tenant incidents reported in audits. |
| Technical leadership | Mentoring engineers, incident guidance, runbooks, interviews, and hiring recommendations. |

The posting's focus on fault behavior, sustained throughput, safe change, and production signals is well supported by the resume. Its strongest project examples for this role are **Keystone**, a Go transactional metadata store using Raft, MVCC, gRPC, and Prometheus, and the **high-throughput streaming data-plane pipeline** using Kafka and AWS analytics services. This portfolio presents that connection through project artifacts and operational outcomes rather than claiming a specific OCI team's internal design.

## Oracle and OCI context

Oracle presents OCI as a cloud platform where infrastructure, data, and applications support enterprise workloads. Its public resiliency guidance explains that OCI organizes infrastructure into regions and availability/fault domains, with physical isolation and redundant systems as building blocks. The company's documentation describes OCI core networking and connectivity as designed for high availability, while also distinguishing Oracle's cloud-infrastructure responsibilities from customers' workload-level architecture and recovery decisions.

This context matters to the role because a platform's availability is not created by a single retry or replica. It comes from explicit failure domains, known consistency/availability behavior, capacity and overload policies, safe lifecycle operations, and signals that let engineers detect and recover from faults. That is an engineering interpretation of the job posting in light of Oracle's public OCI architecture documentation.

## Company / role sources

- [Oracle Careers — Principal Core Infrastructure Engineer, Req. 348886](https://careers.oracle.com/en/sites/jobsearch/job/348886/)
- [Oracle Cloud Infrastructure — Networking Overview](https://docs.oracle.com/en-us/iaas/Content/Network/Concepts/overview.htm)
- [Oracle Cloud Foundation — Regions and Availability Domains](https://docs.oracle.com/en/cloud/foundation/cloud_architecture/governance/regions.html)
- [Oracle Cloud Foundation — Infrastructure Resilience](https://docs.oracle.com/en/cloud/foundation/cloud_architecture/resilience/infrastructure.html)
- [Oracle OCI — Shared Responsibility Model for Resiliency](https://docs.oracle.com/en-us/iaas/Content/cloud-adoption-framework/oci-shared-responsibility.htm)
- [Oracle OCI — Resiliency guidance](https://docs.oracle.com/en-us/iaas/Content/cloud-adoption-framework/era-resiliency.htm)
- [Oracle Cloud Infrastructure](https://www.oracle.com/cloud/)

## Portfolio implementation notes

The site includes all 15 work-experience bullets from the supplied resume and links all 23 user-listed project/source-code entries. Technical Demo links are shown only for projects with demo URLs supplied by the user: TradeSentinel, AskMyStore, Strangers, and Oxide-HV. The IEEE paper and certificate appear in a separate research section. A custom generated data-center image is used as a CSS background, with animated text, a moving conceptual systems diagram, and a searchable project catalog. The diagram is explicitly described as conceptual; it does not represent Oracle's proprietary architecture or live telemetry. LinkedIn and a footer are omitted as requested.
