# Lab 01 – Basic Switching & Connectivity

## Ziel
Aufbau eines einfachen Layer-2-Netzwerks und Überprüfung der Konnektivität
zwischen mehreren Endgeräten.

## Topologie
- 1x Cisco Switch
- 2x PCs
- Alle Geräte im selben Netzwerk

## IP-Adressierung
| Gerät | IP-Adresse | Subnetz |
|------|------------|---------|
| PC1  | 192.168.1.10 | /24 |
| PC2  | 192.168.1.11 | /24 |

## Durchführung
- Endgeräte mit dem Switch verbinden
- IP-Adressen manuell konfigurieren
- Switch über CLI überprüfen

## Verifikation
- Ping von PC1 zu PC2
- `show mac address-table`
- `show interfaces status`

## Ergebnis
Die Endgeräte können erfolgreich miteinander kommunizieren.
Der Switch lernt die MAC-Adressen dynamisch.

## Gelernt
- Funktionsweise eines Layer-2-Switches
- MAC-Adress-Learning
- Grundlegende CLI-Navigation

### Hinweis
Der Switch wird mit Default-Konfiguration betrieben, um den Fokus
auf grundlegendes Layer-2-Switching und Konnektivität zu legen.
