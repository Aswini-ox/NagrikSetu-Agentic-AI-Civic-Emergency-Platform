# 🇮🇳 NagrikSetu — Agentic AI Civic Emergency & Resolution Platform
LIVE DEMO :https://nagriksetu-agentic-ai-civic-emergency-722f.onrender.com

> **Predict. Prioritize. Coordinate. Track. Verify.**

NagrikSetu is an **Agentic AI-powered civic emergency response platform** that transforms citizen complaints into coordinated, trackable, and evidence-based resolution workflows.

Instead of simply collecting complaints, NagrikSetu uses multiple specialized AI agents to **understand incidents, assess urgency, prioritize emergencies, coordinate departments, optimize field resources, monitor SLAs, verify physical resolution, and keep citizens informed.**

---

## 🚨 Problem

Traditional civic complaint systems often stop at:

**Complaint → Ticket Number → Department**

This creates several challenges:

* 🚨 Emergency complaints may not receive the right priority.
* 🏢 Multiple departments may need to coordinate.
* 🔄 Duplicate citizen reports can create fragmented responses.
* ⏱️ Delayed responses may go unnoticed until the SLA is breached.
* 👷 Field completion may be difficult to verify.
* 📍 Resolution evidence may not prove that the work happened at the reported location.
* 👥 Citizens may not know what is happening after submitting a complaint.
* 🌧️ Weather-related risks can create sudden infrastructure emergencies.

NagrikSetu addresses this by creating an **intelligent closed-loop civic response system**.

---

# 💡 Our Solution

NagrikSetu connects the complete civic emergency lifecycle:

```text
Predict
   ↓
Citizen Report
   ↓
Understand
   ↓
Prioritize
   ↓
Orchestrate
   ↓
Optimize Resources
   ↓
Department Response
   ↓
Track SLA
   ↓
Field Completion
   ↓
Verify Evidence
   ↓
Citizen Confirmation
   ↓
Resolve / Reopen
   ↓
Learn
   ↓
Predict Again
```

The platform is designed around one principle:

> **Don't just register the problem. Coordinate the response and verify the outcome.**

---

# 🤖 Agentic AI Workflow

NagrikSetu uses specialized agents that collaborate through an orchestrated workflow.

| Agent                           | Responsibility                                        |
| ------------------------------- | ----------------------------------------------------- |
| 🧠 Multimodal Triage Agent      | Understands citizen text, images and incident context |
| 🌦️ Weather & Disaster Agent    | Detects weather/disaster-related risk                 |
| 🚨 Priority Agent               | Assigns P0–P4 emergency priority                      |
| 🎯 Orchestrator Agent           | Creates and coordinates the response workflow         |
| 💧 Drainage Agent               | Handles waterlogging and drainage tasks               |
| 💦 Water Agent                  | Handles water-related infrastructure issues           |
| 🛣️ Roads Agent                 | Handles road inspection and repair                    |
| 🚦 Traffic Agent                | Manages traffic disruption                            |
| 🆘 Disaster Response Agent      | Coordinates emergency response                        |
| ⏱️ SLA Monitoring Agent         | Tracks deadlines and escalation risk                  |
| 👷 Field Verification Agent     | Verifies field evidence and location                  |
| 📢 Citizen Notification Agent   | Keeps citizens informed                               |
| 🔎 Hotspot Agent                | Identifies recurring civic risk zones                 |
| 📦 Resource Optimizer Agent     | Recommends suitable field teams                       |
| 👥 Crowd Intelligence Agent     | Detects duplicate/related reports                     |
| 🖼️ Evidence Intelligence Agent | Assists with before/after evidence analysis           |
| 🔄 Response Simulation Agent    | Estimates response scenarios                          |
| 💬 Citizen Feedback Agent       | Supports reopen/partial-resolution workflows          |

---

# 🌧️ Example: Flooded Main Road

Consider this citizen report:

> **"Heavy rain has flooded the main road. Water is entering nearby houses and vehicles cannot pass."**

### Step 1 — Citizen Report

The citizen submits:

* Description
* Photo
* Location
* Incident category

NagrikSetu creates:

```text
Ticket: NGS-2026-0042
Status: RECEIVED
```

---

### Step 2 — AI Triage

The Multimodal Triage Agent identifies:

```text
Weather Event      → Heavy Rain
Incident           → Flooding / Waterlogging
Infrastructure     → Main Road
Safety Risk        → High
Affected Context   → Residential + Traffic
```

---

### Step 3 — Priority

The Priority Agent evaluates the incident using factors such as:

* Severity
* Public safety risk
* Infrastructure criticality
* Affected population
* Location
* Weather context
* Time sensitivity

Example result:

```text
Priority → P0 EMERGENCY
SLA      → 2 Hours
```

---

### Step 4 — Multi-Agent Coordination

The Orchestrator creates coordinated tasks:

```text
                 ┌── Drainage Agent
                 │
Citizen Report ──┼── Traffic Agent
                 │
                 ├── Roads Agent
                 │
                 └── Disaster Response Agent
```

Different agents can work on different parts of the same incident.

---

# 🔗 Intelligent Task Dependencies

NagrikSetu supports dependencies between tasks.

Example:

```text
Drainage Task
      ↓
Water Level Reduced
      ↓
Road Inspection
      ↓
Road Repair
```

If the road is still flooded, the Roads Agent remains:

```text
WAITING FOR DEPENDENCY
```

After drainage is completed:

```text
DEPENDENCY SATISFIED
        ↓
ROAD AGENT ACTIVATED
```

This allows the response workflow to adapt dynamically.

---

# ⏱️ SLA Monitoring & Escalation

Every incident receives a response target based on its priority.

| Priority     | Example SLA |
| ------------ | ----------: |
| P0 Emergency |     2 hours |
| P1 Critical  |     4 hours |
| P2 High      | 12–24 hours |
| P3 Moderate  | 24–48 hours |
| P4 Low       |    72 hours |

Possible SLA states:

```text
🟢 HEALTHY
🟠 AT RISK
🔴 BREACHED
```

If an incident approaches its deadline without sufficient progress, the Monitoring Agent can trigger an escalation workflow.

---

# 📍 Field Verification

NagrikSetu does not immediately mark a task as resolved when a worker clicks **Complete**.

Instead, the worker submits:

* Before evidence
* After evidence
* Task completion details
* Location

The Verification Agent evaluates:

```text
Before Evidence
       +
After Evidence
       +
Location Match
       +
Task Completion
       ↓
Verification Result
```

Example:

```text
Worker Distance: 23 meters
Allowed Radius: 50 meters

Result: VERIFIED
```

This creates an evidence-based resolution workflow.

> AI-assisted verification helps reduce the risk of unverified closures; it is not claimed to be perfect fraud detection.

---

# 👥 Citizen Confirmation

After field verification, citizens can see the complete incident timeline:

```text
✓ Reported
✓ Analyzed
✓ Prioritized
✓ Teams Assigned
✓ Work Completed
✓ Verified
✓ Citizen Notified
```

The citizen can also provide feedback:

```text
✅ Yes, Resolved

⚠️ Partially Fixed

🔄 Reopen Issue
```

If the citizen reports that the issue still exists, the incident can be reopened and the relevant response workflow can be activated again.

---

# 🗺️ Civic Digital Twin

NagrikSetu provides a civic situation view containing:

* Active incidents
* Emergency zones
* Flood risk
* Traffic disruption
* Field teams
* Infrastructure risks
* Hotspots
* Response activity

This creates a unified operational view for civic response teams.

---

# 🌦️ Weather & Disaster Intelligence

The platform supports a unified weather and disaster workflow.

Examples include:

* Heavy rain
* Flooding
* Waterlogging
* Cyclone
* Strong winds
* Thunderstorms
* Lightning-related infrastructure damage
* Fallen trees
* Road damage
* Drainage failures
* Water leakage
* Power infrastructure damage
* Building damage
* Coastal flooding

The predictive workflow is:

```text
Weather Signal
      ↓
Risk Analysis
      ↓
Hotspot Detection
      ↓
Preventive Mission
      ↓
Citizen Reports
      ↓
Emergency Response
      ↓
Verification
      ↓
Resolution
```

Where external data is not connected, the platform clearly labels demonstration data as **SIMULATED / DEMO DATA**.

---

# 🔎 Crowd Intelligence

Multiple citizens may report the same incident.

For example:

```text
Report A:
"Waterlogging near Main Road"

Report B:
"Road flooded near bus stop"

Report C:
"Vehicles cannot cross Main Road"
```

The Crowd Intelligence Agent can identify them as related reports and cluster them around a common incident:

```text
NGS-2026-0042
       ↑
 ┌─────┼─────┐
 A     B     C
```

This helps reduce duplicate response workflows.

---

# 📦 Resource Optimizer

The Resource Optimizer Agent can recommend field teams based on:

* Distance
* Availability
* Current workload
* Required skills
* Estimated arrival time

Example:

```text
Team A → 1.8 km → ETA 18 min
Team B → 0.9 km → ETA 9 min
Team C → 2.4 km → ETA 22 min

AI Recommendation → Team B
```

These values are demonstration estimates unless connected to real operational data.

---

# 🔮 Response Simulation

NagrikSetu can demonstrate alternative response scenarios.

Example:

```text
RESPOND NOW
      ↓
Lower estimated impact

        VS

DELAY RESPONSE
      ↓
Higher estimated impact
```

This allows command-center users to explore possible response strategies.

All simulation results are clearly labelled as **AI DEMO ESTIMATES** when they are not based on live operational data.

---

# 🚨 Emergency War Room

For major incidents, NagrikSetu provides a dedicated command-center view.

It can display:

* P0 emergency incidents
* Live incident map
* Active agents
* Field teams
* SLA timers
* Weather risk
* Affected areas
* Response timeline
* Escalation status

This creates a unified emergency response workspace.

---

# 📊 Dashboard

The NagrikSetu Command Center provides a real-time operational overview.

### Key Metrics

* Active Incidents
* Emergencies
* SLA At Risk
* Resolved Today

### Live Map

Incident markers are categorized by priority:

```text
🔴 P0 Emergency
🟠 P1 Critical
🟡 P2 High
🔵 P3 Moderate
⚪ P4 Low
```

### Agent Activity

The dashboard shows:

```text
Triage Agent       → Analyzing
Orchestrator       → Planning
Drainage Agent     → In Progress
Traffic Agent      → Active
Roads Agent        → Waiting
SLA Monitor        → Tracking
Verification       → Pending
```

---

# 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │      Citizen        │
                    │  Web / Mobile UI    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   FastAPI Backend   │
                    └──────────┬──────────┘
                               │
                 ┌─────────────┼─────────────┐
                 │             │             │
                 ▼             ▼             ▼
          ┌───────────┐ ┌───────────┐ ┌───────────┐
          │ AI Agents │ │  Weather  │ │   Crowd   │
          │           │ │  Engine   │ │Intelligence│
          └─────┬─────┘ └─────┬─────┘ └─────┬─────┘
                │             │             │
                └─────────────┼─────────────┘
                              ▼
                    ┌─────────────────────┐
                    │    Orchestrator     │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
        ┌──────────┐     ┌──────────┐     ┌──────────┐
        │Departments│    │ Resources │    │ SLA/Task │
        └─────┬────┘     └──────────┘     └─────┬────┘
              │                                  │
              └────────────────┬─────────────────┘
                               ▼
                    ┌─────────────────────┐
                    │ Field Verification  │
                    └──────────┬──────────┘
                               ▼
                    ┌─────────────────────┐
                    │ Citizen Confirmation│
                    └─────────────────────┘
```

---

# 🛠️ Technology Stack

## Frontend

* React
* Vite
* TypeScript
* Tailwind CSS
* Lucide React
* Recharts
* Leaflet
* React Leaflet

## Backend

* Python
* FastAPI
* Pydantic
* SQLAlchemy

## Database

* SQLite

## AI

* Google Gemini API
* Deterministic fallback/demo mode when the API is unavailable

## Maps

* Leaflet
* OpenStreetMap

## Verification

* Haversine distance calculation
* Evidence-based workflow

---

# 📁 Project Structure

```text
NagrikSetu-Agentic-AI-Civic-Emergency-Platform/
│
├── frontend/
│
├── backend/
│   ├── agents/
│   │   ├── triage_agent.py
│   │   ├── weather_agent.py
│   │   ├── priority_agent.py
│   │   ├── orchestrator_agent.py
│   │   ├── drainage_agent.py
│   │   ├── water_agent.py
│   │   ├── road_agent.py
│   │   ├── traffic_agent.py
│   │   ├── disaster_agent.py
│   │   ├── monitoring_agent.py
│   │   ├── verification_agent.py
│   │   ├── notification_agent.py
│   │   ├── hotspot_agent.py
│   │   ├── resource_agent.py
│   │   ├── crowd_agent.py
│   │   ├── evidence_agent.py
│   │   └── simulation_agent.py
│   │
│   ├── api/
│   ├── models/
│   ├── schemas/
│   ├── services/
│   ├── database/
│   └── main.py
│
├── data/
├── screenshots/
├── demo/
├── .env.example
├── .gitignore
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
└── README.md
```

---

# ⚙️ Installation

## 1. Clone the repository

```bash
git clone https://github.com/Aswini-ox/NagrikSetu-Agentic-AI-Civic-Emergency-Platform.git
cd NagrikSetu-Agentic-AI-Civic-Emergency-Platform
```

## 2. Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend:

```text
http://localhost:5173
```

---

## 3. Backend

Open another terminal:

```bash
cd backend

python -m venv .venv

.venv\Scripts\activate

pip install -r requirements.txt

python -m uvicorn main:app --reload
```

Backend:

```text
http://localhost:8000
```

API documentation:

```text
http://localhost:8000/docs
```

---

# 🔐 Environment Variables

Create a `.env` file:

```env
GEMINI_API_KEY=your_api_key_here
```

Never commit real API keys.

Use:

```text
.env
```

in `.gitignore`.

Provide:

```text
.env.example
```

for configuration reference.

---

# 🎬 Demo Workflow

The recommended demonstration scenario is:

```text
Heavy Rain
     ↓
Flooded Main Road
     ↓
Citizen Report
     ↓
Multimodal Triage
     ↓
P0 Emergency
     ↓
Multi-Agent Orchestration
     ↓
Drainage + Traffic + Roads + Disaster Response
     ↓
Task Dependency
     ↓
SLA Monitoring
     ↓
Resource Optimization
     ↓
Field Worker
     ↓
Before / After Evidence
     ↓
Location Verification
     ↓
Verified Resolution
     ↓
Citizen Confirmation
```

---

# 🧪 Demo Mode

NagrikSetu includes a demonstration workflow that can be executed without depending completely on external AI services.

Example demo incident:

```text
Ticket:
NGS-2026-0042

Incident:
Heavy Rain + Flooding + Road Blockage

Priority:
P0 Emergency

SLA:
2 Hours
```

Demo actions can include:

```text
ANALYZE INCIDENT
ACTIVATE EMERGENCY
DISPATCH TEAMS
COMPLETE DRAINAGE
ACTIVATE ROAD RESPONSE
COMPLETE ROAD TASK
SUBMIT FIELD EVIDENCE
VERIFY RESOLUTION
NOTIFY CITIZEN
SIMULATE RESPONSE
OPTIMIZE RESOURCES
CLUSTER REPORTS
REOPEN ISSUE
RESET DEMO
```

---

# 🌍 Responsible AI

NagrikSetu is designed with responsible AI principles.

### Transparency

Important AI-generated outputs should be shown with their relevant factors and clearly labelled when simulated.

### Human Oversight

The platform supports human decision-making rather than claiming to replace civic authorities.

### Evidence-Based Resolution

Resolution workflows use evidence and location checks instead of relying only on a completion button.

### Simulation Disclosure

If weather, population, response time, resource availability, or impact values are simulated, they are clearly marked as:

**DEMO DATA**

or

**SIMULATED**

### No False Government Integration Claims

NagrikSetu does not claim direct government-system integration unless a real API or authorized integration exists.

---

# 🎯 Why NagrikSetu?

Traditional systems often answer:

> **"Did you register the complaint?"**

NagrikSetu asks:

> **"Did the right teams respond, was the work completed, and can the resolution be verified?"**

That changes the workflow from:

```text
Complaint Management
```

to:

```text
Agentic Civic Operations
```

---

# 🏆 Hackathon

Built for:

## Bharat Agentic 2026

**Powered by AIKart**

Domain:

### GovTech

Focus:

### Agentic AI for Civic Emergency Response

Project:

### NagrikSetu

---

# 👩‍💻 Team

**Team:** VeraX

**Members:**

* Aswini R I
* Charumathi S
* Aishwarya B

**College:**

VSB College of Engineering Technical Campus, Coimbatore

**Department:**

B.E. Computer Science and Engineering

---

# 🚀 Future Scope

NagrikSetu can be extended with:

* Real-time weather APIs
* Government civic APIs
* Emergency service integrations
* IoT water-level sensors
* Smart-city infrastructure data
* Real-time traffic APIs
* Multilingual voice reporting
* WhatsApp/SMS notifications
* Satellite/weather imagery
* Advanced geospatial analytics
* Predictive infrastructure maintenance
* Real field-worker mobile applications

---

# ⭐ Core Idea

> **NagrikSetu doesn't just collect civic complaints.**
>
> **It understands the incident, prioritizes the emergency, coordinates the response, monitors the deadline, verifies the physical outcome, and keeps the citizen in the loop.**

## Predict. Prioritize. Coordinate. Track. Verify.

🇮🇳 **NagrikSetu — From Citizen Report to Verified Resolution.**
