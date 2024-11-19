### **Hack 4: RFID Tag Cloning**

## **Introduction**
Radio-Frequency Identification (RFID) uses electromagnetic fields to identify and communicate with tags. RFID is commonly found in:
- Key fobs and access cards.
- Warehouse asset tracking systems.
- Public transportation cards.

The Flipper Zero allows you to:
- **Read RFID tags** to analyze their properties.
- **Clone RFID tags** onto writable cards.
- **Emulate RFID tags** for troubleshooting.

> **Note**: Ensure you have permission to read or clone RFID tags, as unauthorized use is illegal.

---

## **Step-by-Step Guide**

### **1. Access the RFID Application**
- Turn on the Flipper Zero.
- Navigate to **Applications > RFID**.
- Select **Read RFID**.

---

### **2. Scan the RFID Tag**
- Hold the RFID tag close to the Flipper Zero’s sensor.
- Wait for the device to display the tag details, including:
  - **Tag Type** (e.g., ISO 14443A).
  - **Tag ID** and memory size.

**Example Output**:
```
Tag ID: 00123456789A
Type: ISO 14443A
Memory: 1 KB
```

---

### **3. Save the Tag Data**
- After scanning, select **Save**.
- Name the tag (e.g., “Office Key”) for future reference.

---

### **4. Clone the RFID Tag**
- Insert a writable RFID tag into the Flipper Zero’s writable field.
- Navigate to **Write RFID** and select the saved tag.
- Confirm to write the data onto the blank RFID card.

---

### **5. Emulate the RFID Tag**
- Navigate to **Saved Tags** in the RFID application.
- Select the tag to emulate and press **Emulate**.
- Test by holding the Flipper Zero near an RFID reader.

---

## **Practical Applications**
- **Backup Tags**: Create duplicates of essential RFID tags.
- **Security Testing**: Assess the security of RFID-based systems.
- **Educational Use**: Understand how RFID technology works.

---

## **Tips and Warnings**
- **Tag Compatibility**: Encrypted or proprietary tags may not be clonable.
- **Ethical Use**: Only clone RFID tags you own or have permission to test.
- **Organize Tags**: Use clear names for saved tags for quick access.

---

[← Back to FlipGuard](./README.md)
