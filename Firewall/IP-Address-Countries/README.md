# Country IP Address Lists for MikroTik

A collection of country-based IP address lists formatted for MikroTik RouterOS.

## Overview

This repository provides ready-to-import MikroTik address lists for multiple countries. Each file contains IPv4 and/or IPv6 network ranges converted into MikroTik RouterOS script format (`.rsc`).

These lists can be used for:

* Geo-based firewall filtering
* Traffic classification
* Routing policies
* Access control
* Security automation
* Domestic and international traffic separation

## Repository Structure

```text
Country-IP-Lists/
├── Iran/
│   ├── Iran-IP-ipv4.rsc
│   └── Iran-IP-ipv6.rsc
├── Germany/
│   ├── Germany-IP-ipv4.rsc
│   └── Germany-IP-ipv6.rsc
├── United-States/
│   ├── United-States-IP-ipv4.rsc
│   └── United-States-IP-ipv6.rsc
└── README.md
```

## MikroTik Import

Upload the desired file to your MikroTik router and execute:

```bash
/import file-name=filename.rsc
```

## Example

```rsc
/ip firewall address-list add address=103.111.69.0/24 list=IRAN-IR
```

## Compatibility

* MikroTik RouterOS v6
* MikroTik RouterOS v7

## Notes

* IP allocations may change over time.
* Lists should be updated periodically.
* Verify rules in a test environment before deploying to production.

## License

This project is provided as-is for educational and operational use.
