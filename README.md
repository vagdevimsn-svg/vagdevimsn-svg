## Vagdevi Meka — Senior ServiceNow Developer

ServiceNow developer (6 years on the platform, 8+ in IT) focused on **ITOM and CMDB**: Discovery, Service Mapping, Event Management/AIOps and CSDM-aligned data quality, plus ITSM/ITAM automation, IntegrationHub/REST integrations and Now Assist. Banking, healthcare and telecom environments (PCI-DSS, SOX, HIPAA).

### Featured projects

Independently written portfolio projects with synthetic data. None of this is employer or client code.

**[snow-cmdb-data-quality](https://github.com/vagdevimsn-svg/snow-cmdb-data-quality)** — CSDM-style CMDB health checks
- 9 checks (stale Discovery, duplicates, orphans, services without dependencies or business application, retired CIs in use) with severity and remediation
- Table API client with paging, retry/backoff and OAuth; HTML dashboard, CSV remediation worklist, score history, CI gate
- Python · TOML rules · Docker · GitHub Actions · 32 tests

**[snow-event-correlation](https://github.com/vagdevimsn-svg/snow-event-correlation)** — Event Management-style alert correlation
- Normalize → de-dup on message_key → CI binding → maintenance suppression and flap detection → service correlation → one prioritized incident
- Webhook service and an idempotent ServiceNow incident forwarder (correlation_id); 80% noise reduction on the sample run
- Python (stdlib only) · Docker · GitHub Actions · 27 tests

Also: [servicenow-scripting-patterns](https://github.com/vagdevimsn-svg/servicenow-scripting-patterns) — Script Include, Business Rule and Scripted REST examples with Node unit tests.

**Platform:** ITOM · Discovery · Service Mapping · Event Management · AIOps · CMDB/CSDM · ITSM · HAM/SAM · IntegrationHub · Scripted REST · Flow Designer · Now Assist  
**Code:** JavaScript (Glide APIs) · Python · Java · React · SQL

**LinkedIn:** [linkedin.com/in/devi-mv-98aa33240](https://www.linkedin.com/in/devi-mv-98aa33240/)  
Open to Senior ServiceNow Developer and ITOM/CMDB roles — contract or full-time, remote/hybrid (Portland, OR area).
