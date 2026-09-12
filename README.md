# CareCall

> Patients leave the hospital. Their risks don't.

AI-powered post-discharge patient follow-up powered by CALL-E.

## Overview

CareCall is a healthcare follow-up platform that uses CALL-E to conduct real AI-powered telephone conversations with patients after emergency discharge.

The platform helps healthcare professionals identify warning signs, detect deterioration trends, prioritize patients who need attention, and maintain continuity of care beyond the hospital visit.

## Why CareCall?

Research has consistently shown that structured post-discharge follow-up can improve outcomes and help detect complications earlier.

Unfortunately, healthcare professionals rarely have the capacity to manually call every discharged patient.

CareCall addresses this challenge by combining:

- Real phone conversations through CALL-E
- Clinical AI analysis
- Risk detection
- Alert generation
- Adaptive follow-up planning

## How It Works

1. Patient is discharged.
2. CareCall schedules follow-up calls.
3. CALL-E conducts a real phone conversation.
4. The conversation is transcribed.
5. Specialized AI agents analyze symptoms and trends.
6. Clinical risk is assessed.
7. Alerts and SBAR summaries are generated.
8. Clinicians review the results from the dashboard.

## AI Architecture

CareCall uses a deterministic and auditable pipeline of specialized AI agents.

### Question Planner Agent

Prepares questions, identifies red flags and tracks pending follow-up items.

### Trend Analyst Agent

Detects deterioration across multiple follow-up calls.

### Clinical Analyst Agent

Extracts symptoms, summarizes conversations and determines risk levels.

### Devil's Advocate Agent

Provides a safety review and can only increase risk, never decrease it.

### Clinical Handoff Agent

Generates structured SBAR clinical summaries.

### Adaptive Scheduler Agent

Determines when the next follow-up should occur.

### AgentTrace

Every decision remains traceable and auditable.

## Technology Stack

### Backend

- .NET 10
- ASP.NET Core
- Entity Framework Core
- SQLite

### Frontend

- Blazor

### AI

- Semantic Kernel
- Azure OpenAI
- CALL-E

### Development Tools

- Visual Studio
- GitHub Copilot

## Dashboard

The dashboard provides:

- Active patients
- Open alerts
- Follow-up history
- Risk evolution
- Transcripts
- SBAR summaries
- AgentTrace records

## Demo

### Video

TODO

### Live Demo

TODO

## CALL-E Hackathon

CareCall was created for the CALL-E: Your Code Is Calling Hackathon.

The project demonstrates how AI-powered voice interactions can improve continuity of care after emergency discharge.

## Disclaimer

CareCall is a hackathon prototype for demonstration purposes only.

It is not a medical device and has not undergone clinical validation.

## Intellectual Property

Copyright © 2026 CareCall Team.

All rights reserved.

This repository is published for demonstration and evaluation purposes as part of the CALL-E Hackathon.

## Final Message

Patients leave the hospital.

Their risks don't.

**Powered by CALL-E. Built for real-world impact.**
