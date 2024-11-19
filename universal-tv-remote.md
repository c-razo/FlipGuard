### **Hack 5: Universal TV Remote**

## **Introduction**
The Flipper Zero can act as a universal remote by capturing and emulating infrared (IR) signals used by TVs, projectors, and other IR-controlled devices. This feature allows you to:
- **Capture IR signals** from remotes.
- **Store signals** for future use.
- **Control multiple devices** with a single tool.

> **Note**: Use this feature responsibly and only on devices you own or have explicit permission to control.

---

## **Step-by-Step Guide**

### **1. Access the IR Application**
- Turn on the Flipper Zero.
- Navigate to **Applications > Infrared (IR)**.

---

### **2. Capture a TV Remote Signal**
- Select **Capture** from the IR menu.
- Point a TV remote at the Flipper Zero’s IR receiver.
- Press a button on the remote (e.g., “Power” or “Volume Up”).
- The Flipper Zero will detect and display the captured signal’s details, such as frequency and protocol.

**Example Output**:
```
Frequency: 38 kHz
Protocol: NEC
```

---

### **3. Save the Captured Signal**
- After capturing the signal, choose **Save**.
- Name the signal (e.g., “TV Power” or “Volume Up”) for easy identification.

---

### **4. Emulate the Signal**
- Navigate to **Saved Signals** in the IR menu.
- Select the signal you want to emulate (e.g., “TV Power”).
- Point the Flipper Zero at your TV or device and activate the signal.
- Verify that the device responds correctly.

---

## **Practical Applications**
- **Consolidate Remotes**: Use the Flipper Zero to replace multiple remotes.
- **Troubleshooting**: Test IR functionality on TVs and other devices.
- **Learn IR Protocols**: Explore how infrared communication works.

---

## **Tips and Warnings**
- **Device Compatibility**: Some devices may use protocols not supported by the Flipper Zero.
- **Ethical Use**: Avoid using this feature in public spaces or on devices without permission.
- **Organize Signals**: Label saved signals clearly to manage multiple devices.

---

[← Back to FlipGuard](./README.md)
