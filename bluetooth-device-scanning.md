### **Hack 7: Bluetooth Device Scanning**

## **Introduction**
The Flipper Zero’s Bluetooth functionality allows you to scan for nearby devices and analyze their signal strength and basic information. This is useful for:
- **Identifying unauthorized devices** in sensitive areas.
- **Testing Bluetooth signal strength and reach.**
- **Learning how Bluetooth communication works.**

> **Note**: Do not use this feature to track or intercept private devices. Always respect privacy and local laws.

---

## **Step-by-Step Guide**

### **1. Access the Bluetooth Application**
- Turn on the Flipper Zero.
- Navigate to **Applications > Bluetooth**.

---

### **2. Enable Bluetooth Scanning**
- Select **Scan for Devices**.
- The Flipper Zero will display nearby Bluetooth-enabled devices, along with details such as:
  - **Device Name**: Identifies the device (if available).
  - **Signal Strength**: Measured in dBm (decibels relative to 1 milliwatt).

**Example Output**:
```
Device Name: Wireless Speaker
Signal Strength: -42 dBm
```

---

### **3. Save or Ignore Results**
- Highlight a device and select:
  - **Save**: Store the device information for future reference.
  - **Ignore**: Skip saving the device.

---

### **4. Analyze Device Information**
- Review saved devices to:
  - Identify their Bluetooth profiles (e.g., Audio, Data Transfer).
  - Determine their approximate distance based on signal strength.

---

## **Practical Applications**
- **Security Audits**: Identify unauthorized Bluetooth devices in secure areas.
- **Range Testing**: Measure signal strength and determine optimal device placement.
- **Learn Bluetooth Protocols**: Explore how Bluetooth devices communicate.

---

## **Tips and Warnings**
- **Privacy**: Avoid scanning or saving data for devices that do not belong to you.
- **Signal Interference**: Be aware of environmental factors that may impact Bluetooth signals.
- **Legal Compliance**: Follow local regulations when analyzing Bluetooth signals.

---

[← Back to FlipGuard](./README.md)
