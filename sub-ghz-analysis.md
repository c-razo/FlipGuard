### **Hack 3: Sub-GHz Signal Analysis**

## **Introduction**
Sub-GHz refers to low-frequency wireless communication (below 1 GHz) used in devices like garage door openers, remote controls, and IoT systems. The Flipper Zero can:
- **Scan for Sub-GHz signals**.
- **Analyze signal properties**, such as frequency and protocol.
- **Replay or emulate signals** for testing.

> **Note**: Always ensure you are authorized to analyze or replay signals. Unauthorized use may be illegal.

---

## **Step-by-Step Guide**

### **1. Access the Sub-GHz Application**
- Turn on the Flipper Zero.
- Navigate to **Applications > Sub-GHz**.

---

### **2. Scan for Sub-GHz Signals**
- Select **Frequency Analyzer** from the Sub-GHz menu.
- Press the **Scan** button to start detecting nearby signals.
- Observe the signal details, such as frequency, protocol, and signal strength.

**Example Output**:
```
Frequency: 433.92 MHz
Protocol: UNKNOWN
Signal Strength: -50 dBm
```

---

### **3. Record the Signal**
- When a signal is detected, select **Record** from the menu.
- Save the signal with a descriptive name (e.g., “Garage Remote Open”).
- The signal will be stored in the Flipper Zero’s Sub-GHz directory.

---

### **4. Replay the Signal**
- Navigate to **Saved Signals** in the Sub-GHz menu.
- Select the signal you wish to replay (e.g., “Garage Remote Open”).
- Point the Flipper Zero at the target device and activate the signal.
- Verify the device responds as expected.

---

## **Practical Applications**
- **Security Testing**: Evaluate the security of Sub-GHz devices.
- **Educational Use**: Learn about wireless communication protocols.
- **Troubleshooting**: Test the functionality of Sub-GHz devices.

---

## **Tips and Warnings**
- **Legal Considerations**: Signal replay may be restricted in your area. Follow local laws.
- **Protocol Support**: Some protocols may not be recognized by the Flipper Zero.
- **Ethical Use**: Limit testing to devices you own or have explicit permission to analyze.

---

[← Back to FlipGuard](./README.md)
