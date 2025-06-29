### 1.7 🧭 Definition of Locations in SAP TM

---

### ✅ Use  
This process is used to **define locations** in **SAP Transportation Management (SAP TM)** so they can be used in transportation planning, orders, and resource management.

---

### 🛠️ Prerequisites  

Before defining a location, complete the following in **Customizing**:

**Path:**  
`SCM Basis → Integration → Basic Settings for Creating the System Landscape`

- ✅ Name Logical Systems  
- ✅ Assign Logical Systems to a Client  
- ✅ Maintain Business Systems Group  
- ✅ Assign Logical System and Queue Type  

🔄 *(Optional)* Enable **geocoding** via:  
`SAP NetWeaver → General Settings → Set Geocoding`

---

### ⚙️ Process  

1. Open **SAP NetWeaver Business Client**
2. Navigate to:  
   `Master Data → Transportation Network → Locations → Define Location`
3. Enter:
   - Location name
   - Location type
   - Click **Create**
4. Fill the following tab pages:

#### 📌 Tab Pages

- **General**  
  - Standard identifiers  
  - Geographical data  
  - Owning business partner  
  - Priority

- **Address**  
  - Contact and address details  
  - Communication info  
  - 🌐 *Entering address data allows system to calculate geolocation (country code required)*

  > Note: SAP TM does **not** ship a geocoding tool. You can integrate a third-party one if needed.

- **Alt. Identifiers**  
  - Add alternate IDs for location  
  - See: *Definition of Alternative Location Identifiers*

- **TM (Transportation Mgmt.)**  
  - Goods wait time  
  - Air cargo security settings  
  - E.g., shipper security status

- **Resources**  
  - Resource restrictions  
  - Operating times for inbound/outbound activities

- **Addit. (Additional)**  
  - Custom fields and attributes  
  - Configurable in:  
    `Transportation Management → Master Data → General Settings → Maintain Freely-Definable Attributes`

5. Click **Save**

---

### 🏁 Result  

- You’ve successfully **created a location**
- You can now **view, change, or reuse** it by navigating to:  
  `Master Data → Transportation Network → Define Location`
- The location is ready to be used in:
  - **Forwarding orders**
  - **Resource definitions**
  - **Transportation planning**
