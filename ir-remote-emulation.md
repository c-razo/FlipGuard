### **Hack 2: IR Remote Emulation**

## **Introduction**
Infrared (IR) is a communication technology commonly used in remote controls for TVs, air conditioners, and other devices. The Flipper Zero can:
- **Capture IR signals** from remotes.
- **Store the signals** for future use.
- **Emulate remote controls** to operate devices.

> **Note**: Use this feature only on devices you own or have explicit permission to control.

---

## **Step-by-Step Guide**

### **1. Access the IR Application**
- Turn on the Flipper Zero.
- Navigate to **Applications > Infrared (IR)**.

---

### **2. Capture an IR Signal**
- Select **Capture** from the IR menu.
- Point a remote control at the Flipper Zero's IR receiver.
- Press a button on the remote to transmit a signal.
- The Flipper Zero will display the captured signal’s details, such as frequency and protocol.

**Example Output**:
```
Frequency: 38 kHz
Protocol: NEC
```

---

### **3. Save the Captured Signal**
- After capturing the signal, choose **Save**.
- Name the signal (e.g., “TV Volume Up”) for future reference.

---

### **4. Emulate the Signal**
- Navigate to **Saved Signals** in the IR menu.
- Select the signal you want to emulate (e.g., “TV Volume Up”).
- Point the Flipper Zero at the target device and activate the signal.
- Verify the device responds as expected.

---

## **Practical Applications**
- **Universal Remote**: Consolidate multiple remotes into one device.
- **Test IR Devices**: Troubleshoot IR-based appliances.
- **Learn IR Protocols**: Explore how infrared communication works.

---

## **Tips and Warnings**
- **Compatibility**: Some devices use unique protocols that may not work with the Flipper Zero.
- **Ethical Use**: Avoid using this feature on devices in shared or public spaces without permission.
- **Storage Management**: Organize saved signals for easy access.

---

[← Back to FlipGuard](./README.md)
