---
layout: page
title: Loads & Shipment types
---

## Loads

### FTL & LTL
- Used in Road secnario
- Refers to full truck load and less than full truck load
- Full truck load can depend on volume and capacity of a truck.
- Example if a truck has a capacity of 20ton and a single material of 20ton is placed on it, even if it has space it will be considered as full truck load.
- Similarly if the volume is full just by 12ton of weight, still it will be FTL.

---

### FCL & LCL
- Used in ocean secnario
- Concept similar to FTL & LTL

---

## Shipment Types

### **Single Leg Shipment**
- Use only one leg like only road or ship

### **Multi Leg Shipment**
- Requires multiple legs.

```
    A -> B (Road)
    B -> C (Ship)
    C -> D (Road)
```

### **Direct Shipment**
- Vendor directly ships to customer

### **Milk Runs**
- Truck works in shifts to transfer goods from production center to distribution center.
- A FTL is used.

### **Multi Carrier Shipment**
- Multiple carriers are involved
- They are always multi leg shipment


