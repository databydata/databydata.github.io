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

3. **Transportation Resource:** 
- Physical resources like trucks, trailers, containers.
- Required for capacity planning and freight order assignment.

```
    Where to create: TM WEB UI
    Master Data > Resource Management > Create Vechicle resource.
```

4. **Product:**
- The goods being transported.
- Must have relevent transportation details (weight, volumne, dimensions).

```
    Tcode: MM01 (Create)/ MM02 (Change)
    System: S/4HANA
    Note: Product master gets transferred to TM via integration
```

5. **Transportation Network:**
- Defines which locations are connected via which route and transportation modes..
- Includes transit duration, distance, and modes like Road, Rail, Sea, etc.

```
    Where to create: TM WEB UI
    Master Data > Transportation Network
```
