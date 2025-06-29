## 📍 Location in SAP TM (Simplified)

### ✅ Definition  
A **Location** is a physical or logical place where goods or resources are stored, moved, or processed (e.g., factories, warehouses, or customer sites).

---

### 🚚 Purpose / Use  
Locations are used to define **source**, **destination**, and **transit points** in a transportation process.

**Example:**  
To ship a product from your factory to a customer:
- Source Location → **Production Plant**  
- Transit Point → **Port** or **Warehouse**  
- Destination → **Customer**

---

### 🏷️ Location Types (Examples)  
Each location is assigned a **type** to help categorize it.

| Location Type       | Code  | Example Use                        |
|---------------------|-------|------------------------------------|
| Production Plant     | 1001  | Where goods are manufactured       |
| Distribution Center  | 1002  | Where goods are stored for dispatch|
| Customer             | 1010  | Final delivery location            |
| Port                 | 1100  | For sea freight transit            |
| Airport              | 1110  | For air freight                    |
| Terminal / Hub       | 1030 / 1140 | Midpoint for transferring goods    |

> 🔹 *Location types are just labels. They don’t control any business logic.*

---

### 🔗 Where It’s Used  
Locations are used across SAP TM processes:
- To create **transportation zones**, **lanes**, **schedules**
- To define **resources** (e.g., vehicles, drivers)
- To set **restrictions** (e.g., some vehicles can’t deliver to a certain location)
- For **orders, freight units**, and **transportation activities**

---

### 🔄 Integration with SAP ERP  
Locations can be **transferred from SAP ERP** to SAP TM using the **Core Interface (CIF)** to keep systems in sync.
