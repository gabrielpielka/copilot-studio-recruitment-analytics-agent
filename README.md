# Copilot Studio Recruitment Analytics Agent

An AI-powered recruitment analytics solution built with **Microsoft Copilot Studio**, **Power Automate**, **Power Query**, and **Excel**.

This project demonstrates how a conversational AI agent can be combined with workflow automation and data transformation to create a practical business reporting solution.

---

## Overview

The agent can:

- interpret reporting requests for different time periods
- retrieve recruitment summary data through Power Automate
- generate structured business summaries
- offer email delivery of the report
- generate and send a PDF attachment automatically

---

## Architecture

![Architecture](images/cover-architecture.png)

**Flow:**

User → Copilot Studio Agent → Power Automate → Excel + Power Query → AI Analysis → PDF & Email

---

## Demo

### Copilot chat interaction

![Chat Demo 1](images/chat-demo-1.png)

![Chat Demo 2](images/chat-demo-2.png)

---

## Copilot Studio topic logic

### Period selection

![Topic Logic 1](images/topic-logic-1.png)

### Date calculation logic

![Topic Logic 2](images/topic-logic-2.png)

### Email delivery option

![Topic Logic 3](images/topic-logic-3.png)

---

## Power Automate workflows

### Analytics flow

![Power Automate Flow 1](images/power-automate-flow-1.png)

### Email and PDF delivery flow

![Power Automate Flow 2](images/power-automate-flow-2.png)

---

## Data preparation

Raw recruitment data is transformed using **Power Query** before being consumed by the Copilot agent.

The transformation process includes:
- filtering
- grouping
- aggregation
- creation of monthly company-level summary tables

![Power Query](images/power-query-summary-company.png)

---

## Output examples

### Email result

![Email Result](images/email-result.png)

### Generated PDF report

![PDF Report](images/pdf-report.png)

---

## Key Features

- Conversational reporting interface
- Dynamic period selection
- Monthly recruitment analytics
- Top company and rejection reason analysis
- AI-generated structured summaries
- PDF report generation
- Automated email delivery

---

## Tech Stack

- Microsoft Copilot Studio
- Power Automate
- Power Query
- Excel
- Outlook / Email automation
- PDF generation workflow

---

## Repository Contents

- `copilot-topic/final-topic.yaml` → exported Copilot Studio topic logic
- `images/` → demo screenshots
- `docs/` → supporting notes

---

## Privacy Note

The original source data contains business-sensitive and personal information.

For this reason:
- the source dataset is **not included** in this repository
- screenshots were sanitized
- sensitive details were blurred or anonymized where necessary

---

## Why this project matters

This project is a practical example of how **AI agents + workflow automation + data preparation** can be combined into a real business solution.

Instead of being a simple chatbot, the agent acts as a workflow assistant that:
- understands a reporting request
- triggers automation
- processes data
- generates output
- delivers the result
