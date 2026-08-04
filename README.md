# Cisco Nexus Dashboard (cisco-nexus)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

APIs for managing and monitoring Cisco Nexus data center switches and network infrastructure.

**APIs.json:** [https://developer.cisco.com/site/nexus/](https://developer.cisco.com/site/nexus/)

## Tags

- Data Center
- Infrastructure
- Network Automation
- Networking
- SDN
- Switches

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Cisco NX-API REST

RESTful API for programmatic access to Nexus switches using HTTP/HTTPS.

- **Human URL:** [https://developer.cisco.com/docs/nx-os/](https://developer.cisco.com/docs/nx-os/)
- **Base URL:** `https://{switch-ip}/api`

#### Tags

- CLI
- Configuration
- Monitoring
- REST

#### Properties

- [Documentation](https://developer.cisco.com/docs/nx-os/#!working-with-nx-api)
- [OpenAPI](openapi/cisco-nexus-nxapi-rest.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.cisco.com/docs/nx-os/#!authentication)
- [SDK](https://developer.cisco.com/docs/cisco-nexus-3000-and-9000-series-nx-api-rest-sdk-user-guide-and-api-reference/latest/)
- [Getting Started](https://developer.cisco.com/docs/cisco-nexus-3000-and-9000-series-nx-api-rest-sdk-user-guide-and-api-reference/latest/getting-started-with-the-cisco-nexus-3000-and-9000-series-nx-api-rest-sdk/)
- [API Reference](https://developer.cisco.com/docs/nexus-model/latest/)

### Cisco NX-API CLI

API that accepts show commands and configuration commands in CLI format.

- **Human URL:** [https://developer.cisco.com/docs/nx-os/#!working-with-nx-api-cli](https://developer.cisco.com/docs/nx-os/#!working-with-nx-api-cli)
- **Base URL:** `https://{switch-ip}/ins`

#### Tags

- CLI
- Configuration
- Show Commands

#### Properties

- [Documentation](https://developer.cisco.com/docs/nx-os/#!nx-api-cli)
- [SDK](https://github.com/CiscoDevNet/nxapi-learning-labs)
- [Sandbox](https://devnetsandbox.cisco.com/RM/Topology)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Nexus Dashboard REST API

Unified API for Nexus Dashboard Insights, Orchestrator, and Fabric Controller.

- **Human URL:** [https://developer.cisco.com/docs/nexus-dashboard/latest/](https://developer.cisco.com/docs/nexus-dashboard/latest/)
- **Base URL:** `https://{nexus-dashboard}/api/v1`

#### Tags

- ACI
- Dashboard
- Fabric Controller
- Insights
- Orchestration

#### Properties

- [Documentation](https://developer.cisco.com/docs/nexus-dashboard/)
- [API Reference](https://developer.cisco.com/docs/nexus-dashboard/#!api-reference)
- [Getting Started](https://developer.cisco.com/docs/nexus-dashboard/latest/getting-started/)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Nexus Dashboard Fabric Controller API

REST API for managing and automating Nexus and MDS fabrics including LAN, SAN, and IP Fabric for Media deployments.

- **Human URL:** [https://developer.cisco.com/docs/nexus-dashboard-fabric-controller/latest/](https://developer.cisco.com/docs/nexus-dashboard-fabric-controller/latest/)
- **Base URL:** `https://{nexus-dashboard}/appcenter/cisco/ndfc/api/v1`

#### Tags

- EVPN
- Fabric Management
- LAN
- NDFC
- SAN
- VXLAN

#### Properties

- [Documentation](https://developer.cisco.com/docs/nexus-dashboard-fabric-controller/latest/)
- [Getting Started](https://developer.cisco.com/docs/nexus-dashboard-fabric-controller/latest/getting-started/)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Nexus Dashboard Orchestrator API

API for multi-site orchestration of ACI, Cloud ACI, and DCNM fabrics with policy management and segmentation.

- **Human URL:** [https://developer.cisco.com/docs/nexus-dashboard-orchestrator/latest/](https://developer.cisco.com/docs/nexus-dashboard-orchestrator/latest/)
- **Base URL:** `https://{nexus-dashboard}/appcenter/cisco/ndo/api/v1`

#### Tags

- ACI
- Multi-Site
- Orchestrator
- Policy Management
- Segmentation

#### Properties

- [Documentation](https://developer.cisco.com/docs/nexus-dashboard-orchestrator/latest/)
- [Getting Started](https://developer.cisco.com/docs/nexus-dashboard-orchestrator/latest/getting-started/)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Nexus Dashboard Insights API

API for network analytics, telemetry, anomaly detection, and troubleshooting across data center fabrics.

- **Human URL:** [https://developer.cisco.com/docs/nexus-dashboard-insights/latest/](https://developer.cisco.com/docs/nexus-dashboard-insights/latest/)
- **Base URL:** `https://{nexus-dashboard}/appcenter/cisco/ndi/api/v1`

#### Tags

- Analytics
- Anomaly Detection
- Insights
- Telemetry
- Troubleshooting

#### Properties

- [Documentation](https://developer.cisco.com/docs/nexus-dashboard-insights/latest/)
- [Getting Started](https://developer.cisco.com/docs/nexus-dashboard-insights/latest/getting-started/)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco DCNM REST API

Data Center Network Manager API for managing Nexus fabric deployments.

- **Human URL:** [https://developer.cisco.com/docs/data-center-network-manager/](https://developer.cisco.com/docs/data-center-network-manager/)
- **Base URL:** `https://{dcnm-server}/rest`

#### Tags

- DCNM
- EVPN
- Fabric Management
- VXLAN

#### Properties

- [Documentation](https://developer.cisco.com/docs/data-center-network-manager/)
- [Use Cases](https://developer.cisco.com/docs/data-center-network-manager/#!use-cases)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco NETCONF/YANG API

Model-driven API using YANG data models for Nexus devices.

- **Human URL:** [https://developer.cisco.com/docs/nx-os/#!working-with-netconf](https://developer.cisco.com/docs/nx-os/#!working-with-netconf)
- **Base URL:** `netconf://{switch-ip}:830`

#### Tags

- Automation
- Model-Driven
- NETCONF
- YANG

#### Properties

- [Documentation](https://developer.cisco.com/docs/nx-os/#!working-with-netconf)
- [GitHub Repository](https://github.com/YangModels/yang/tree/master/vendor/cisco/nx)
- [Tutorials](https://developer.cisco.com/learning/labs/tags/Nexus/)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco NX-OS RESTCONF API

HTTP-based protocol for configuring YANG-defined data on Nexus switches supporting XML and JSON payload encodings.

- **Human URL:** [https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/106x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-106x/chapter-2.html](https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/106x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-106x/chapter-2.html)
- **Base URL:** `https://{switch-ip}/restconf`

#### Tags

- HTTP
- Model-Driven
- RESTCONF
- YANG

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/106x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-106x/chapter-2.html)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco NX-OS gNMI/gRPC API

gRPC Network Management Interface for streaming telemetry and configuration management on Nexus switches.

- **Human URL:** [https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/106x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-106x/m-gnmi.html](https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/106x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-106x/m-gnmi.html)
- **Base URL:** `grpc://{switch-ip}:50051`

#### Tags

- gNMI
- gRPC
- Model-Driven
- Streaming
- Telemetry

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/106x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-106x/m-gnmi.html)
- [GitHub Repository](https://github.com/CiscoDevNet/nx-telemetry-proto)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco NX-OS Model-Driven Telemetry API

Streaming telemetry interface for real-time operational data collection from Nexus switches using YANG models.

- **Human URL:** [https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/102x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-release-102x/m-n9k-model-driven-telemetry-101x.html](https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/102x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-release-102x/m-n9k-model-driven-telemetry-101x.html)
- **Base URL:** `grpc://{switch-ip}:50051`

#### Tags

- Dial-Out
- Monitoring
- Streaming
- Telemetry
- YANG

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/102x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-release-102x/m-n9k-model-driven-telemetry-101x.html)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco NX-OS Python SDK API

Python Software Development Kit for programmatic access to Nexus 9000 Series switch modules including interfaces, VLANs, ACLs, and routes.

- **Human URL:** [https://developer.cisco.com/docs/nx-os/cisco-nexus-9000-series-python-sdk-user-guide-and-api-reference/](https://developer.cisco.com/docs/nx-os/cisco-nexus-9000-series-python-sdk-user-guide-and-api-reference/)
- **Base URL:** `https://{switch-ip}`

#### Tags

- Automation
- On-Box
- Python
- SDK

#### Properties

- [Documentation](https://developer.cisco.com/docs/nx-os/cisco-nexus-9000-series-python-sdk-user-guide-and-api-reference/)
- [GitHub Repository](https://github.com/CiscoDevNet/NX-SDK)
- [Postman Collection](collections/cisco-nexus-nxapi-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-nexus-nxapi-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Developer Portal](https://developer.cisco.com/)
- [GitHub Organization](https://github.com/CiscoDevNet)
- [Training](https://developer.cisco.com/learning/labs/tags/Nexus/)
- [Sandbox](https://devnetsandbox.cisco.com/)
- [Support](https://developer.cisco.com/site/support/)
- [Status Page](https://status.cisco.com/)
- [Code Examples](https://developer.cisco.com/codeexchange/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
