# Awesome-Smart-Electrical-Grid-Demand-Management-Platforms

# Top Smart Electrical Grid Demand Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Virtual Power Plants, Demand Response & Distributed Energy Resource Orchestration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Smart Electrical Grid Demand Management**. These tools help utilities, aggregators, and energy service companies balance supply and demand by coordinating distributed energy resources (DERs) — batteries, EV chargers, heat pumps, and flexible loads — through demand response programs, virtual power plants (VPPs), and grid-aware dispatch optimization.

**Examples** include AutoGrid, Uplight, Enel X, Stem, EnergyHub, Voltus, Piclo, Leap, Grid4C, and Fluence Energy (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom dispatch optimization, and transparent grid coordination — ideal for utilities prioritizing data sovereignty, researchers advancing flexibility algorithms, and aggregators avoiding per-device licensing fees.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AutoGrid](https://www.auto-grid.com/)**  
  Enterprise DER management platform with AI-powered demand response, VPP orchestration, and grid services optimization for utilities and aggregators.

- **[Uplight](https://uplight.com/)**  
  Energy management platform connecting utilities with customers for demand response, energy efficiency, and electrification programs.

- **[Enel X](https://www.enelx.com/)**  
  Advanced energy services business line of Enel Group delivering smart energy products across electrification, e-mobility, demand response, and virtual power plants .

- **[Stem](https://www.stem.com/)**  
  AI-driven energy storage and VPP platform with Athena for optimizing battery dispatch, demand charge reduction, and grid services.

- **[EnergyHub](https://www.energyhub.com/)**  
  Distributed energy resource management platform (DERMS) for utilities to aggregate and control thermostats, batteries, EV chargers, and solar inverters.

- **[Voltus](https://www.voltus.co/)**  
  Commercial and industrial VPP operator aggregating demand response and DER assets into wholesale energy markets .

- **[Piclo](https://piclo.energy/)**  
  Flexibility marketplace platform connecting flexibility providers with network operators for local grid congestion management.

- **[Leap](https://www.leap.energy/)**  
  Software platform enabling DERs to participate in wholesale energy markets through automated bidding and dispatch .

- **[Grid4C](https://www.grid4c.com/)**  
  AI-powered analytics for utilities with demand forecasting, load disaggregation, and grid edge intelligence.

- **[Fluence Energy](https://fluenceenergy.com/)**  
  Energy storage technology and services company with Fluence Mosaic for AI-powered bidding and dispatch optimization.

## Open-Source GitHub Projects

- **[FlexMeasures](https://github.com/FlexMeasures/flexmeasures)**  
  Leading open-source energy management system (EMS) platform for optimizing energy flexibility, built for startups and ESCOs . Think of it as the "Lego Mindstorms" of smart energy planning — combining out-of-the-box algorithms, UIs, and APIs with modular architecture for behind-the-meter asset orchestration. Handles domestic buildings with heat pumps and EVs under dynamic tariffs, neighborhoods with grid capacity constraints, office buildings with multiple EVs, and SME/industrial facilities with heat buffering. Developers can simulate and test without physical hardware. Contributed to LF Energy and adopted by smart energy startups worldwide including Thiink Inc (US) and iRasus Technologies (India) .

- **[OpenLEADR-rs](https://github.com/OpenLEADR/openleadr-rs)**  
  Rust implementation of the OpenADR demand response protocol, housed under LF Energy . OpenADR is the open standard for automated demand response communication between grid operators and customer systems. Supports OpenADR 3.0 (production-ready) and 3.1 (beta), with a subscription feature for real-time grid signals and CLI for debugging/prototyping. Built with reliability, memory safety, and efficient deployment (single binary) in mind. Active Dutch grid-aware EV charging use case with ElaadNL and Tweede Golf. Funding secured through 2026. Python SDK and compliance plugin also available .

- **[FRS-FASTDERMS](https://github.com/LBNL-ETA/frs-fastderms)**  
  Flexible Resource Scheduler from Lawrence Berkeley National Laboratory (LBNL) . Hierarchical controller managing distributed energy resources in a distribution substation or feeder to provide firm commitment of power flow at the substation head. Comprises day-ahead stochastic optimization, intra-hour MPC generating DER dispatch base points, and real-time PID controller maintaining substation power around base points. Reference controller for DOE FAST-DERMS Architecture. BSD-3-Clause licensed. Includes aggregator controller and simulation components with PNNL's GridAPPS-D .

- **[VPP-Sim](https://github.com/)**  
  Modular open-source framework for developing and deploying ML-driven strategies in virtual power plants . Bridges the gap between forecasting research and downstream business value by connecting state-of-the-art forecasting with economic optimization. Containerized microservices architecture with FastAPI backend, React/TypeScript frontend, Apache Kafka for real-time data streaming, TimescaleDB for time-series storage, MLflow for ML lifecycle management, and PuLP for economic dispatch. Designed for researchers to evaluate how ML model improvements tangibly impact VPP operational performance .

- **[Virtual Power Plant (vinerya)](https://github.com/vinerya/virtual-power-plant)**  
  Comprehensive Python library for virtual power plant management, simulation, and research . Features REST API with endpoints for users, resources, sites, customers, optimization (dispatch, schedule, backtest, stochastic, realtime, distributed), simulated trading, tariffs, V2G, protocols (OCPP, OpenADR), demand response, alerts, and WebSocket channels for real-time telemetry and grid events. Includes web console for fleet overview. 88 GitHub stars, actively maintained .

- **[Virtual Power Plant Optimization System](https://github.com/2308087369/Virtual-power-plants)**  
  Advanced VPP multi-resource coordination system built on oemof-solph framework with CBC solver for linear programming . Models PV, wind, gas turbine, energy storage, adjustable loads (chiller, heat pump), and grid interaction. Features six scheduling modes (renewable_storage, adjustable_storage, traditional, no_renewable, storage_only, full_system), multi-objective optimization (cost minimization, profit maximization), ancillary services (frequency regulation, spinning reserve), demand response, and hierarchical dispatch (day-ahead, intraday, real-time). 35 GitHub stars .

- **[VOLTTRON](https://github.com/VOLTTRON/volttron)**  
  Distributed control and sensing software platform from Pacific Northwest National Laboratory (PNNL) for managing energy systems . Agents communicate with physical devices and resources to independently manage HVAC systems, electric vehicles, distributed energy, and building loads. Supports MODBUS, BACnet, OpenADR, and sMAP historian. Low CPU/memory footprint, language-agnostic, with security features including memory protection, authentication, and authorization. Used by Lawrence Berkeley and Oak Ridge National Laboratories .

- **[VOLTTRON AEMS](https://github.com/VOLTTRON/volttron-pnnl-aems)**  
  Autonomous Energy Management Software (AEMS) from PNNL continuously optimizing DER operations in small and medium commercial buildings . Minimizes energy consumption and cost while maximizing decarbonization benefits from building electrification. Initially manages rooftop air conditioners and heat pumps, extendable to water heaters, storage, EV charging, and solar PV. Supports both energy efficiency and grid service features. Apache 2.0 licensed, USDOE funded .

- **[NREL Virtual Battery Aggregator](https://github.com/NREL/virtual-battery-aggregator)**  
  Algorithms for DER management system platform from National Renewable Energy Laboratory (NREL) . Aggregates DERs modeled as batteries, creates virtual battery model for centralized grid control, and dispatches power setpoints to individual DERs based on desired virtual power setpoint from grid control. Integrates with co-simulation frameworks for buildings, DERs, and distribution systems. Python-based .

- **[NREL Real-Time Dispatcher](https://github.com/)**  
  Dispatches aggregated power of DER plant on electrical distribution network to provide real-time grid services . Services include voltage support of distribution network, VPP at substation with power factor support, and operating reserves for automatic generator control. Integrates with local power plant controller and BESS to smooth volatile net power output. Can integrate with day-ahead scheduler for strategic charge/discharge .

- **[DRAF (Demand Response Analysis Framework)](https://github.com/DrafProject/draf)**  
  Analysis and decision support framework for local multi-energy hubs focusing on demand response . Uses mixed integer linear programming optimization with pandas, Plotly, elmada, GSEE, and Jupyter. Features time series analysis tools (DemandAnalyzer, PeakLoadAnalyzer), parameterizable component templates (battery, EV, CHP, heat pump, PV, wind, fuel cell, electrolyzer, hydrogen storage, DAC), multi-objective optimization with Pyomo/GurobiPy, and plotting tools (heatmaps, Sankeys, pareto plots). Runs on Windows, macOS, Linux .

- **[REScoopVPP](https://github.com/)**  
  Smart building ecosystem for energy communities with Community-driven Flexibility Box (COFYbox) and COFYcloud . COFYbox is an open, collaborative building controller based on Home Assistant, using off-the-shelf products. Integrates domestic equipment including inverters, heat pumps, and EV chargers. Community tools include demand/production forecasting algorithms, dynamic pricing module, and OpenADR-based explicit demand response. Large-scale experimentation in Belgium, France, Germany, Spain, and UK .

- **[PyPESOL](https://github.com/)**  
  Python Peer-to-Peer Energy Sharing Optimization Library . Lightweight, modular framework for cost optimization in P2P energy sharing scenarios. Supports individual and group-based optimization, self-contained user group formation with scalable heuristics. Built on Pyomo and CBC open-source LP solver. Handles 23.2k prosumers and 92.4k consumers across 182M edges with 0.13s per optimization problem. Presented at ACM e-Energy 2025 .

### Additional Strong Open-Source Options

- **[FOCUS:LFM](https://www.salzburgresearch.at/en/projekt/focuslfm/)** — Modular open-source aggregator middleware for local flexibility management in Austria . Coordinates EV chargers, heat pumps, batteries, and smart appliances using OpenADR 3.1 and MQTT 5. Empowers DSOs to monitor, request, and validate flexibility activation. Aligns with EU Network Code on Demand Response and Austria's Common Flexibility Platform .

- **CSE Toolkit** — Privacy-first RFP response generation with local embedding model and MCP tools.

- **[OpenADR Python SDK](https://github.com/OpenLEADR/openleadr-python)** — Python implementation of OpenADR protocol for demand response integration.

- **EV Charging Management Platform** — Full-stack platform with AI dispatching, V2G, and VPP capabilities .

**Frameworks for building custom systems**: Combine **FlexMeasures** for behind-the-meter flexibility optimization, **OpenLEADR-rs** for OpenADR-based grid communication, **FRS-FASTDERMS** for hierarchical DER scheduling, **VPP-Sim** for ML-driven strategy evaluation, and **Virtual Power Plant (vinerya)** for comprehensive VPP management and simulation to build a complete self-hosted grid demand management stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Smart grid demand management tools must comply with utility regulations, grid interconnection standards, cybersecurity requirements (NERC CIP, IEC 62443), and data protection regulations. Incorrect dispatch decisions can impact grid stability.
- Self-hosted open-source solutions require proper security hardening, protocol certification, and validation against grid codes before operational deployment.

---

**Made for utility operators, DER aggregators, energy service companies, and developers building smart grid demand management platforms.**  
Let's make smart electrical grid demand management more open, flexible, and grid-friendly.
