# Testing Results

| Test | Expected Result | Result |
|------|-----------------|--------|
| VLAN database | Required VLANs active | PASS |
| 802.1Q trunking | Trunks operational | PASS |
| RSTP | CORE-SW1 root | PASS |
| VTP | ENTERPRISE domain | PASS |
| HSRP | CORE-SW1 active | PASS |
| OSPF | FULL adjacency | PASS |
| DHCP | Clients receive addresses | PASS |
| APP-SERVER → Gateway | Reachable | PASS |
| DNS-SERVER → Gateway | Reachable | PASS |
| DNS-SERVER → APP-SERVER | Reachable | PASS |
| VLAN 10 → VLAN 20 | Blocked by ACL | PASS |
| VLAN 10 → VLAN 50 | Allowed | PASS |
| USER-PC1 → Internet | Reachable | PASS |
| FINANCE-PC1 → Internet | Reachable | PASS |
| SALES-PC1 → Internet | Reachable | PASS |
| SSH → CORE-SW1 | Successful | PASS |