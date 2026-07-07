# IP Addressing Plan

| VLAN | Department | Network | Default Gateway |
|------|------------|----------------|----------------|
|10|HR|192.168.10.0/24|192.168.10.1|
|20|Finance|192.168.20.0/24|192.168.20.1|
|30|IT|192.168.30.0/24|192.168.30.1|

---

## DHCP

Each VLAN receives IP addresses automatically from the router using DHCP pools.

---

## NAT

PAT is configured on the Enterprise Router to allow internal devices to access external networks.
