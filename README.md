# RainONE
“RainONE: A modular communications engineering platform for PBX, V2X, and IoT systems aligned with ITU/IEEE/3GPP Standards.
# RainOne – Unified Communications Platform

RainOne is the flagship platform of **RAININ Group**, combining enterprise PBX, JTAPI-based softphone, and IoT vehicle communications middleware into a unified architecture.  
It is developed by **RAININ Technologies** (product factory) and operated by **Raintel Communications** (service provider).

---

## 🚀 Vision
To engineer reliable, scalable communications for enterprises and smart mobility — bridging telecom, transport, and IoT.

---

## 🏗️ Architecture
- **PBX Core**: Java 17 / Spring Boot implementation of SIP, RTP, JTAPI.
- **Softphone**: JTAPI-based client with modular APIs.
- **API Gateway**: REST/WebSocket endpoints for integration.
- **Vehicle Comms Middleware**: DSRC, C-V2X, CAN, ITS-G5 protocol support.

📖 See `/docs/architecture` for diagrams and specifications.

---

## ✨ Features
- Enterprise UCaaS (Unified Communications as a Service).
- IoT V2X stack for smart mobility.
- Developer APIs for third-party integration.
- Training bootcamps and sales enablement playbooks.

---

## ⚙️ Getting Started
**Prerequisites**: Java 17, Spring Boot 3, Docker.  
**Setup**:
```bash
git clone https://github.com/3mman/RainONE.git
cd RainONE
mvn clean install
docker-compose up
