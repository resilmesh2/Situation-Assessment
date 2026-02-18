# Situation-Assessment

Contextualizes threats into system/service risk: 
- CASM: automated internal/external attack surface scanning and vulnerability acquisition (NVD), orchestrated with Temporal-based workflows. 
- ISIM (Neo4j): central graph model storing assets/services/vulns/dependencies (REST + GraphQL). 
- CSA (Critical Service Awareness): maps missions/services and computes asset criticality using ISIM + network centrality inputs. 
- NSE: network-wide risk aggregation + projection (current & future posture). 
- NDR: traffic analysis + anomaly detection + RCA + XAI. 
- SACD: consolidated dashboard UI for SA data. 
- AIBAST: AI-driven automated security testing (planned for later Pilot 2 phases). 
- Landing Page: entry point linking to platform services.