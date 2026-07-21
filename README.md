# 🛡️ CivicShield AI

> **Securing Public Services Through Intelligent Cyber Defense**

CivicShield AI is an AI-powered Security Operations Center (SOC) platform built for organizations that protect society—including Government Departments, Educational Institutions, Healthcare Organizations, NGOs, and Municipal Offices.

The platform automatically ingests security events, performs deterministic and AI-assisted threat analysis, correlates related alerts into incidents, and helps security teams investigate and respond faster without requiring expensive enterprise SIEM/SOAR infrastructure.

---

# 📖 Overview

Many public-sector and small organizations lack dedicated cybersecurity teams and enterprise-grade SOC solutions. As a result, security alerts are often ignored, misclassified, or investigated too late.

CivicShield AI bridges this gap by providing an intelligent cyber defense platform capable of:

- Automated security alert ingestion
- AI-assisted threat analysis
- Deterministic risk scoring
- Threat confidence calculation
- Incident correlation
- Investigation assistance
- Executive-level incident summaries
- Multi-tenant organization management

---

# 🚀 Key Features

## 🔐 Authentication & Security

- JWT Authentication
- Refresh Token Support
- Role-Based Access Control (RBAC)
- Organization-based Tenant Isolation
- Secure Password Hashing
- Protected API Routes

---

## 🏢 Multi-Tenant Organization Management

- Organization Registration
- Organization Settings
- User Management
- Tenant Isolation
- Organization-specific Security Data

---

## 🚨 Alert Management

- Security Alert Ingestion
- Duplicate Detection
- Alert Fingerprinting
- Alert Search
- Advanced Filtering
- Pagination
- Alert Details
- Alert Lifecycle Tracking

---

## 🧠 AI-Powered Threat Analysis

Every alert undergoes intelligent analysis that produces:

- Threat Confidence Score
- Risk Score
- False Positive Likelihood
- Threat Classification
- Supporting Evidence
- IOC Matching
- MITRE ATT&CK Mapping
- Business Impact Assessment
- Executive Summary
- Containment Recommendations

---

## 🎯 Deterministic Threat Engine

The platform combines AI reasoning with deterministic cybersecurity rules including:

- Threat Intelligence Matching
- Asset Criticality
- IOC Scoring
- Historical Context
- Whitelist Detection
- Maintenance Window Recognition
- Trusted Automation Detection
- Scanner Detection
- Backup Process Detection
- Monitoring System Detection

---

## 🔍 Threat Intelligence

Supports organization-specific Threat Intelligence indicators:

- IP Address
- Domain
- URL
- File Hash
- CVE

CRUD APIs are available for managing indicators.

---

## 🔄 Incident Correlation

Automatically groups related alerts into incidents using:

- Source IP
- Destination IP
- Hostname
- Username
- Indicators of Compromise
- Threat Intelligence
- Time Window Correlation
- Duplicate Detection

---

## 📊 Dashboard

Real-time SOC dashboard including:

- Total Alerts
- Critical Alerts
- Open Incidents
- Resolved Incidents
- Threat Trends
- Severity Distribution
- Classification Distribution
- Risk Distribution
- Threat Confidence Distribution
- Connector Health
- Recent Alerts
- Recent Incidents

---

## 🔌 Integrations

Supports multiple alert ingestion methods:

- REST API
- CSV Upload
- Firebase
- Webhook Connectors
- Custom Security Integrations

---

## 📈 Investigation Workspace

Provides analysts with:

- AI Investigation Reports
- Evidence Collection
- Incident Timeline
- Threat Intelligence Matches
- MITRE ATT&CK Mapping
- Investigation History

---

# 👥 User Roles

### Organization Administrator

- Manage Organization
- Manage Users
- Configure Integrations
- Organization Settings

### Security Officer

- Monitor Security Posture
- Review Critical Incidents
- Escalate Threats
- Investigation Oversight

### Security Team Member

- Alert Triage
- Incident Investigation
- Threat Validation
- Alert Analysis

### Alert Source

- Automated Security Event Ingestion

### Super Administrator

- Platform Administration
- System Monitoring
- Tenant Management

---

# 🔄 System Workflow

```text
Security Source
      │
      ▼
Connector Validation
      │
      ▼
Alert Ingestion
      │
      ▼
Threat Intelligence Matching
      │
      ▼
Deterministic Analysis
      │
      ▼
OpenAI Threat Analysis
      │
      ▼
Threat Confidence
      │
      ▼
Risk Scoring
      │
      ▼
Threat Classification
      │
      ▼
Alert Correlation
      │
      ▼
Incident Creation
      │
      ▼
MITRE ATT&CK Mapping
      │
      ▼
Business Impact Analysis
      │
      ▼
Executive Summary
      │
      ▼
Containment Recommendations
      │
      ▼
Investigation Workspace
      │
      ▼
Incident Resolution
```

---

# 🏗️ Technology Stack

## Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- Axios
- React Query

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Socket.IO

## AI Services

- OpenAI API
- Deterministic Threat Confidence Engine
- Threat Intelligence Matching

---

# 📁 Project Structure

```
CivicShield/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── src/
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   ├── models/
│   └── package.json
│
└── README.md
```

---

# 🔒 Security Features

- JWT Authentication
- Secure Password Hashing
- Organization Isolation
- Protected Routes
- Threat Intelligence Validation
- Duplicate Alert Prevention
- Risk-Based Analysis
- Evidence Persistence

---

# ⚡ AI Capabilities

- Threat Classification
- Threat Confidence Scoring
- Risk Assessment
- False Positive Detection
- IOC Matching
- MITRE ATT&CK Mapping
- Business Impact Analysis
- Executive Security Summaries
- Containment Recommendations

---

# 🚀 Future Enhancements

- Email Notifications
- Microsoft Sentinel Integration
- Splunk Integration
- Elastic Integration
- VirusTotal Integration
- AbuseIPDB Integration
- Real-time WebSocket Alerts
- Security Compliance Reports
- PDF Report Generation
- Multi-language Support

---

# 👨‍💻 Developed By

**Arun Kavali**

B.Tech Computer Science Engineering

AI | Cybersecurity | Full Stack Development | Generative AI

---

# 📄 License

This project is developed for educational, research, and demonstration purposes.