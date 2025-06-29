### 1.5 🔄 Transshipment Location

---

### ✅ Definition  
A **transshipment location** is a place where goods are **unloaded from one vehicle** and **reloaded onto another** during the transportation process.

---

### 🚚 Purpose / Use  
Used when:
- Different **carriers** or **modes of transport** are required (e.g., truck → train).
- Goods need to be **consolidated** or **deconsolidated**.

**Example:**  
Goods go from **Location A → Location C**, but must be unloaded at **Location B** to switch trucks.  
➡️ In this case, **Location B** is a transshipment location.

---

### 🏗️ Structure  
A transshipment location is defined by:
- Assigning a **location** to another **location** or a **transportation zone**.

> 📌 If a location is assigned to a transportation zone, **all locations in that zone** can use it as a transshipment point.

⚠️ **Note:** You **cannot assign a location to itself** as a transshipment location.

✅ **Recommendation:**  
Only define transshipment locations that are **actually used** in your transportation scenarios to maintain good system performance.

---

### 🔗 Integration  
To use a transshipment location in a transportation process:
- You must define **transportation lanes** that include it.

**Example Setup:**  
To ship from **Location A → Location C** via **Transshipment Location B**:
1. Define **Location B** as a transshipment location.
2. Create:
   - A **transportation lane** from A → B  
   - A **transportation lane** from B → C

> 🔄 These lanes ensure goods can flow through the transshipment point correctly.

