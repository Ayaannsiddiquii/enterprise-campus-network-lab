# IP Addressing Plan

## VLANs

| VLAN | Name | Subnet | HSRP Gateway |
|------|------|--------|--------------|
| 10 | USERS | 192.168.10.0/26 | 192.168.10.1 |
| 20 | FINANCE | 192.168.20.0/27 | 192.168.20.1 |
| 30 | SALES | 192.168.30.0/27 | 192.168.30.1 |
| 40 | ADMIN | 192.168.40.0/28 | 192.168.40.1 |
| 50 | SERVERS | 192.168.50.0/28 | 192.168.50.1 |
| 99 | MANAGEMENT | 192.168.99.0/28 | 192.168.99.1 |
| 999 | NATIVE | N/A | N/A |

## Servers

| Device | IP |
|--------|----|
| APP-SERVER | 192.168.50.10 |
| DNS-SERVER | 192.168.50.11 |

## Routed Links

| Link | Network |
|------|---------|
| EDGE-ROUTER ↔ CORE-SW1 | 10.0.0.0/30 |
| EDGE-ROUTER ↔ CORE-SW2 | 10.0.0.4/30 |
| EDGE-ROUTER ↔ ISP-EDGE | 10.0.0.8/30 |
