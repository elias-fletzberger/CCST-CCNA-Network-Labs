# Lab 02 - Switch Basic Configuration & Management

## Ziel
Grundlegende Inbetriebnahme, Absicherung und Verwaltung eines Cisco Switches
über CLI und sichere Management-Zugänge.

## Topologie
  ![Topologie](screenshots/topology.png)

## IP-Adressierung
| Gerät | Interface | IP-Adresse |
|------|------------|---------|
| S1 | VLAN 1 (SVI) | 192.168.1.2/24 |
| PC  | NIC | 192.168.1.10/24 |

## Durchgefühte Konfiguration
- Basis-Konfiguration
- Zugriffsschutz (Console / VTY)
- Management-IP
- SSH-Zugriff

## Verifikation
- korrekte Konfiguration über `show running-config`
- SSH Zugriff von PC getestet und erfolgreich
  
  ![SSH Login](screenshots/ssh-login.png)

## Zugriffsschutz
- Switch wird über ein lokales Benutzerkonto verwaltet (`login local`)
- Passwörter verschlüsselt (`secret`)
- Telnet ist deaktiviert, Zugriff erfolgt ausschließlich über SSH
  
## Gelernt
- Sichere Erstkonfiguration eines Switches
- Management-Zugriff via SSH
