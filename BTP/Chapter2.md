---
layout: page
title: BTP Account Setup
---

## 2. Account Setup and Administration
### 2.1 Traial and Commercial Models
**Models (non-commit)**
- SAP BTP Trail  
  For personal usage to get hands on experience with SAP BTP.

- Enterprise Trial  
  For high-touch customers via SAP sales representatives. This trail offers production like environment but in test environment. 

- Free- Tier Model  
  
**Models (commit)**
- Pay-As-You-Go
- CPEA
- Single Service Subscription

### 2.2 Services

##### 2.2.1 Services Discovery and Estimator Tool

https://discovery-center.cloud.sap/index.html

### 2.3 Account Structure and Setup

##### 2.3.1 Account Structure
With a new account trial or paid, a global account is created. This global account is used for billing and to manage subaccounts, members, and entitlements.  

Sub-account lets you structure a global account according to your requirements with regards to members, authorizations, entitlements and quotas.

Global account will have all the services and entitlements are assigned to global account then services can be distributed among different sub-accounts.

```
Structure:

Global Account > Region > Directories > Subaccount > Services

```
##### 2.3.2 Setup
Sub-accounts can be setup based on different requirements.

Like: one set can consist of HR sub-account for dev, Sales sub-accounts for dev, etc.

### 2.4 Administration
##### 2.4.1 Global Account
Main account which is created after creating an account on SAP BTP which holds all the entitlements.

##### 2.4.2 Subaccounts

Accounts within Global Account

##### 2.4.3 Entitlements

Services subscribed in SAP BTP and they are assigned at global account level

##### 2.4.4 Boosters
Service provisioning, Service instance creation, and role collection management are some of the main administrative tasks that have been automated using booster.
