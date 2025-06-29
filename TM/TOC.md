---
layout: page
title: Table Of Content SAP Transportation Management
---

## 1. Master Data

### 1.1 🧑‍💼 Business Partners

> A person, organization, group of persons, or group of organizations in which a company has a business interest.

> When you first create a business partner in the system, the BP role General Business Partner is automatically assigned to the business partner.


TM Specific Data:
1. Identification (BP roles Carrier and Organizational Unit)
2. Vendor Data (BP roles Carrier and Vendor)
3. Vendor Company Org. Data (BP roles Carrier and Vendor)
4. Vendor Org. Data (BP roles Carrier and Vendor)
5. Vendor Partner Determination (BP roles Carrier and Vendor)
6. Customer Data (BP roles Ship-To Party and Sold-To Party)
7. Customer Company Org. Data (BP roles Ship-To Party and Sold-To Party)
8. Customer Org. Data (BP roles Ship-To Party and Sold-To Party)
9. Customer Org. Data (BP roles Ship-To Party and Sold-To Party)
10. Additional texts (BP role Business Partner (Gen.))

```
1. You define a BP in SAP NetWeaver Business Client by choosing Master Data > General > Define Business Partner.
2. Additional roles for BP of type Organization
    2.1 Carrier
    2.2 Ship-To Party and Sold-To Party
    2.3 Vendor
    2.4 Organizational Unit
3. Additional roles for BP of type Person
    3.1 Employee
    3.2 Internet User
    3.3 Contact Person
    3.4 Driver
```

### 1.2 🏢 Organizational Management

> Structures used to represent company hierarchy, departments, and reporting lines.

```
1. You define an organizational model in SAP NetWeaver Business Client (NWBC) by choosing Master Data > Organization > Create Organization and Staffing.

- Sales organization, office, and group

- Purchase organization and group

- Planning and execution organization and group
```

You use organizational units with a Sales organizational unit function to create the following:

1. Forwarding orders

2. Forwarding quotations

3. Forwarding settlements

You use organizational units with a Purchasing organizational unit function to create the following:

1. Freight orders

2. Freight bookings

3. Freight settlements

You use organizational units with an Execution organizational unit function to create the following:

1. Resources 

2. Freight orders



### 1.3 🚛 Transportation Network

You use this component in **SAP Transportation Management (SAP TM)** to define the following master data objects:

- **Location**
    
- **Transportation Zone**
- **Transportation Lane**
- **Schedule**