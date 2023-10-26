---
sidebar_position: 2
---

# Integrations

# Android - Developer Documentation

## **Integration Guide**

### **1. Set Up**

### Dependencies

Add the Quash SDK to your project's build.gradle:

```
implementation 'com.github.Oscorp-HQ:QuashAndroidSDK:1.0.8-beta'
```

### **2. Initialize the SDK**

Initialization should be done preferably in your application's **`onCreate`** method.

```kotlin
Quash.initialize(this, "YOUR_APP_TOKEN")
```

### **3. Activation**

By default, Quash is activated by shaking the device. This action will bring up the bug reporting interface, allowing testers to quickly report an issue.
