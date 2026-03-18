# Architecture

## Core Flow

Approval Request  
↓  
Policy Evaluation  
↓  
AI Brief Generation  
↓  
Recommendation  
↓  
Approval Decision  

---

## Core Objects

- Approval_Request__c
- Approval_Brief__c
- Approval_Recommendation__c
- Approval_Condition__c
- Audit_Log__c

---

## AI Integration

- Named Credential callouts
- Structured payload
- Response stored in Salesforce

---

## Design Principles

- Salesforce-native
- No hardcoded secrets
- Minimal outbound data
- Human-in-the-loop
