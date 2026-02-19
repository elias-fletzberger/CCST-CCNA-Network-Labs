# Lab 04 - Inter-VLAN Routing

## Ziel
Implementierung von Inter-VLAN Routing mittels Router-on-a-Stick,
sodass Geräte in unterschiedlichen VLANs miteinander kommunizieren können.

## Topologie
![Topologie](screenshots/topology.png)

## VLAN-Design
| VLAN | Name | Zweck |
|------|------------|---------|
| 10 | CLIENTS | PCs |
| 20 | SERVERS | Server |
| 99 | NATIVE | natives VLAN |

## IP-Adressierung
| Gerät | VLAN | IP-Adresse |
|------|------------|---------|
| PC1 | 10 | 192.168.10.11/24 |
| PC2 | 10 | 192.168.10.12/24 |
| Server | 20 | 192.168.20.11/24 |
| Router | 10 | 192.168.10.1/24 |
| Router | 20 | 192.168.20.1/24 |
| Router | 99 | 192.168.99.1/24 |
