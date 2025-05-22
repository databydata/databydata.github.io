---
layout: page
title: Master Data in SAP TM
---

In SAP TM, master data is the foundation for all planning and execution processes. Without correct master data, transportation cannot be plnned efficiently.

### 2.1 Key master data objects:
1. **Business Partner:** 
- Represent customers, carriers, vndors, etc.
- Can have multiple roles (e.g., Carrier, Forwarding Agent, Shipper).
- Critical for identifying who is sending, receiving, or transporting goods.

```
    Tcode: BP
    System: S/4HANA
    TIP: Assign roles like "Business Partner(Carrier)" and "Shipper" while creating.
```

2. **Location:** 
- Each warehouse, plant, customer, or vendor is represented as a "Location" in TM.
- Used in planning routes and defining the transportation network.

```
    No direct Tcode.
    Can be viewed in TM web ui under Master Data > Locations.
```

3. **Freight Orders:** 
- Transportation activities are documented in freight orders.
- These contain info about route, time, vehicle, and carrier.

4. **Shipment tracking:**
- SAP TM allows real-time monitorin of shipments.
- Notifications can be triggered in case of delays.

5. **Freight cost settlement:**
- The incurred transportation cost are calculated and checked.
- Then the settlement is done with the carrier or internally.

6. **Analytics and reporting:**
- Companies use SAP TM to analyze KPIs like 

<br>

SAP TM covers the complete transportation process - from order capturing to planning to settlement.