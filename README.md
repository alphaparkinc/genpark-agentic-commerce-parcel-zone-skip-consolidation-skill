# Parcel Zone-Skip Consolidation & Linehaul Injection Optimizer Skill

[![GenPark Official](https://img.shields.io/badge/GenPark-Official%20Skill-blue)](https://www.genpark.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-GenPark-blue)](https://www.linkedin.com/company/92955550)
[![MCP Compliant](https://img.shields.io/badge/MCP-JSON--RPC%202.0-green)](https://modelcontextprotocol.io/)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero%20Stdlib-brightgreen)](https://python.org)

Parcel zone-skipping economics, linehaul truckload cost vs destination injection postal sort savings, and transit time SLA trade-off. Built for GenPark (https://www.genpark.ai).

## 🌐 Official Channels
- **Official Website**: [https://www.genpark.ai](https://www.genpark.ai)
- **LinkedIn Page**: [https://www.linkedin.com/company/92955550](https://www.linkedin.com/company/92955550)

## 🛠️ MCP Tools Exposed
- `evaluate_zone_skip_economic_arbitrage`: Compare direct origin-to-destination parcel shipping vs linehaul consolidation truckload to destination hub.
- `identify_optimal_destination_injection_hub`: Select best regional USPS NDC/SCF or FedEx SmartPost hub based on volume centroid.

## 🚀 Installation & Usage
```bash
python -m genpark_agentic_commerce_parcel_zone_skip_consolidation_skill.server --test
```
