## Segun Sogunle

I build systems that survive their failures.

Most of my work is in distributed systems reliability: Kafka at scale, event-driven
infrastructure, and the failures that pass every health check. Observability has become
excellent at telling us what happened, and is still remarkably poor at telling us what
should have happened.

I am currently building **[Clutta](https://clutta.io)** at
[SEFAS Technologies](https://sefastech.com): completion monitoring for business flows. It
learns how your flows normally run and tells you when one stops partway, with the records
to prove it.

### Selected work

| | |
|---|---|
| **Kafka storage load balancer** | Rebalanced 50,000+ replicas and 17,000+ partition leaders in bounded, disk-gated batches. Cut broker rebalancing from days to two hours and removed maintenance windows from the riskiest routine operation on the estate. |
| **Self-healing subscription activator** | A Go daemon that continuously detects and restores wrongly suspended subscriptions across 9M+ records, with operator kill switches and bounded batching. |
| **Upstream fixes in DataHub** | [#8224](https://github.com/datahub-project/datahub/pull/8224), a configurable fix for a catalog silently attaching wrong schemas to Kafka topics, and [#8222](https://github.com/datahub-project/datahub/pull/8222), repairing the migration command's dry-run path. |
| **IEEE 802.1CB in P4** | Implemented the frame replication and elimination standard clause by clause for smart-grid networks at the Karlsruhe Institute of Technology, with the ONOS control plane needed to orchestrate it. |
| **CSDR** | A polyglot subscriber data repository exposing MySQL, MongoDB and Redis through one OData interface, proven inside a live IMS core under real signalling. MSc thesis, Rhodes University, with distinction. |

### Verifiable

- Thesis: [*A Unified Data Repository for Rich Communication Services*](https://researchrepository.ru.ac.za/items/4d9b4e97-1bd8-4d2a-af38-1c6c0e102dd7), Rhodes University
- Journal: [*An Empirical Study of Automated Classification Tools for Informal Requirements in Large Scale Systems*](https://doi.org/10.1504/IJBIS.2015.069723), IJBIS 19(3), 2015
- Writing: [segunsogunle.com](https://segunsogunle.com), field notes on failures that pass every health check

### Reach me

If you are deep in a system that is failing in ways your dashboards cannot explain, that is
the conversation I most want to have.

[segunsogunle.com](https://segunsogunle.com) · [sefastech.com](https://sefastech.com) · [LinkedIn](https://linkedin.com/in/sogunle)
