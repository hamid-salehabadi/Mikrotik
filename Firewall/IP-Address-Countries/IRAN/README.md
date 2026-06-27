# Iran IPv4 Address List for MikroTik

This repository contains an IPv4 address list of Iranian IP ranges formatted for MikroTik RouterOS.

## File

```text
Iran-IP-ipv4.rsc
```

## Address List Name

```text
IRAN-IR
```

## Example Entry

```rsc
/ip firewall address-list add address=103.111.69.0/24 list=IRAN-IR
```

## Import to MikroTik

Upload the file to your router and run:

```bash
/import file-name=Iran-IP-ipv4.rsc
```

## Use Cases

* Geo-based firewall rules
* Domestic vs international traffic separation
* Routing policies
* Access control and security filtering

## Notes

* IP ranges may change over time.
* Periodic updates are recommended.
* Tested format: MikroTik RouterOS Address List Script (.rsc)

## Source

IP ranges are collected from public IP allocation databases and converted into MikroTik RouterOS address-list format.
