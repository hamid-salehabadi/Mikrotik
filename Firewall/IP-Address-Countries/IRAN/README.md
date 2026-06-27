
# MikroTik Iran IP List

This repository contains a MikroTik `.rsc` file with IP ranges of Iran.

## 📁 File
- IRAN-IR.rsc

## 🚀 How to use on MikroTik

### 1. Upload file to MikroTik
Use Winbox or SCP:

### 2. Import file in MikroTik terminal

### 3. Verify address list

## 🎯 Usage Example

You can use this list for:

- Firewall rules
- Routing policies
- Blocking or allowing traffic by country

Example rule:

/ip firewall filter add chain=forward src-address-list=IRAN action=accept

## ⚠️ Note
This list may need periodic updates due to ISP IP changes.
