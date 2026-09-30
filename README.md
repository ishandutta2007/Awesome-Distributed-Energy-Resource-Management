# Awesome-Distributed-Energy-Resource-Management

## Top Distributed Energy Resource Management (DERMS) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on DER Orchestration, Grid-Edge Control, VPP Aggregation, Hosting Capacity & Distribution Optimization*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Distributed Energy Resource Management Systems (DERMS)**. These systems monitor, forecast, and control DERs—solar, storage, EVs, flexible loads—so utilities and aggregators can maintain grid reliability while maximizing renewable integration.

**Examples** include AutoGrid, Smarter Grid Solutions, Schneider Electric DERMS, Siemens Grid Software, Camus Energy, GE GridOS, Hitachi Energy, EnergyHub, Opus One Solutions, and KrakenFlex (the category leaders).

**Open-source emphasis**: Production DERMS is largely commercial. Open strength lies in **distribution simulation** (OpenDSS, GridLAB-D), **IEEE 1547 DER models** (OpenDER), **middleware** (DERIM, VOLTTRON), and research/prototype control stacks. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AutoGrid, EnergyHub, KrakenFlex](https://www.auto-grid.com/)**  
  DERMS and virtual power plant platforms for utility and aggregator orchestration of flexible DERs at scale.

- **[Smarter Grid Solutions, Camus Energy, Opus One](https://www.smartergridsolutions.com/)**  
  Distribution-focused DERMS for real-time control, constraint management, and grid services.

- **[Schneider Electric DERMS, Siemens Grid Software, GE GridOS, Hitachi Energy](https://www.se.com/)**  
  Enterprise grid software suites from major vendors with DER management, ADMS integration, and advanced analytics.

- **[Other commercial DERMS platforms](https://www.auto-grid.com/)**  
  Additional solutions for VPP, demand response, and multi-asset DER portfolios.

## Open-Source GitHub Projects

- **[OpenDSS (EPRI)](https://sourceforge.net/projects/electricdss/)**  
  Industry-standard open-source distribution system simulator—unbalanced power flow, QSTS, and DER impact studies used by utilities worldwide.

- **[OpenDER (EPRI)](https://github.com/epri-dev/OpenDER)**  
  Open-source DER model implementing IEEE 1547-2018 behaviors for PV and BESS—steady-state and dynamic analysis, interfaced with OpenDSS.

- **[GridLAB-D](https://github.com/gridlab-d/gridlab-d)**  
  Open-source power system simulation and analysis tool designed for distribution automation and smart-grid research, including DER scenarios.

- **[VOLTTRON](https://github.com/VOLTTRON/volttron)**  
  Open distributed sensing and control platform from DOE/PNNL—agent-based framework often used for building and DER coordination research.

- **[DERIM Middleware](https://github.com/iceccarelli/derim-middleware)**  
  Open smart-grid middleware for DER integration—telemetry normalization, CIM-aligned models, time-series storage, and digital twin hooks.

- **[GridOS / experimental DER OS projects](https://github.com/iceccarelli/GridOS)**  
  Emerging open energy operating system concepts—device registration, telemetry, Modbus/MQTT adapters, and basic control workflows.

- **[Mini-DERMS Feeder Controller](https://github.com/ceh6514/Mini-DERMS-Feeder-Controller)**  
  Open educational feeder-level DERMS demo—MQTT telemetry, control loops, demand response events, and operator dashboard.

- **[NREL / lab DERMS control frameworks](https://github.com/NREL/EVSE_DERMS_Controls)**  
  Open control libraries for EVSE and DER coordination with DERMS communication patterns.

### Additional Strong Open-Source Options

- **Grid studies**: OpenDSS + OpenDER for hosting capacity and IEEE 1547 impact analysis.
- **Simulation**: GridLAB-D for detailed distribution and agent-based scenarios.
- **Integration layer**: DERIM or VOLTTRON for multi-protocol DER connectivity.
- **Prototyping**: Mini-DERMS-style stacks for feeder control experiments.
- **Composable stacks**: OpenDSS planning → MQTT/Modbus field agents → open optimizer → operator UI.
- Commercial DERMS still lead in real-time ADMS integration, utility-scale SCADA security, and regulated operations.

**Frameworks for building custom systems**:  
**OpenDSS** and **OpenDER** for analysis; **GridLAB-D** / **VOLTTRON** / **DERIM** for simulation and integration prototypes.  
Commercial DERMS (AutoGrid, EnergyHub, Smarter Grid Solutions, Schneider, Siemens, GE, Hitachi, etc.) provide production control and utility support.  
Research labs and progressive utilities prototype on open tools; operational DERMS almost always runs on commercial platforms. Fully open production DERMS is not yet equivalent to certified utility systems.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- DERMS systems interact with the power grid and can affect reliability and safety. Only authorized entities should deploy control to live assets. Comply with interconnection standards (e.g. IEEE 1547), utility operating procedures, and cybersecurity requirements for operational technology.
- Open-source tools are primarily for research, planning studies, and prototyping—not drop-in replacements for utility-grade DERMS. Commercial platforms provide the integration, support, and operational maturity grid operators require.

---

**Made for utility DER engineers, aggregators, and grid modernization teams.**  
Let's expand open DER modeling and research platforms while recognizing that production DERMS depends on proven commercial systems.
