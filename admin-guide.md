# Admin Guide

---

## Step 1 — Assign Permission Sets

- Approval_Admin
- Approval_Approver
- Approval_Submitter

---

## Step 2 — Configure Policies in Custom Metadata

Define:

- discount thresholds
- margin thresholds
- payment terms
- contract duration

---

## Step 3 — Configure Field Mappings in Custom Metadata

Map:

- discount
- margin
- contract term
- payment terms
- segment
- region

---

## Step 4 — Configure AI

- create Named Credential
- create custom setting record with Named Credential Name, LLM Provider, API Key
- validate connection

# LLM Configuration Model

Smart AI Approvals uses a Bring Your Own LLM (BYOM) approach.

Admins configure the LLM provider connection, credentials within their Salesforce environment.

List of Supported LLM Providers:
- OpenAI
- Gemini
- Groq
- Claude/Databricks
  
---

## Step 5 — Validate

Create test approval:

- brief generated
- recommendation visible
