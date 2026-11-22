# CCNA Labs

> **Summary (EN):** Hands-on CCNA lab portfolio built in Cisco Packet Tracer: VLANs, inter-VLAN routing, OSPF, DHCP/NAT, ACLs, STP/HSRP and IPv6. Each lab documents scenario, addressing plan, configuration (with the *why* behind each command), verification and honest troubleshooting. Documentation is in German. These are lab environments, not production networks.

## Über dieses Repository

Dieses Repository dokumentiert meine praktischen Übungen zu den Themen des **Cisco CCNA**. Jedes Lab hat ein realitätsnahes Szenario (z. B. „kleines Büro mit drei Abteilungen“) und ist so aufgebaut, dass ich jeden Schritt erklären kann:

- **Szenario & Topologie** – Welches Problem wird gelöst?
- **Adressierungsplan** – strukturiert und nachvollziehbar
- **Umsetzung** – die wichtigsten Befehle, jeweils mit Begründung **warum**
- **Verifikation** – `show`- und `ping`-Tests mit Screenshots
- **Troubleshooting** – Fehler, die beim Aufbau wirklich passiert sind, und absichtlich eingebaute Fehler zur Übung
- **Konfigurationen** als Text (`show running-config`), lesbar auch ohne Packet Tracer

> Diese Labs basieren auf den Übungen meiner HTL-Ausbildung und meiner CCNA-Vorbereitung und wurden in Cisco Packet Tracer umgesetzt.

## Labs

| Nr. | Lab | Themen | Status |
|-----|-----|--------|--------|
| 01 | [VLAN & Inter-VLAN-Routing](01-vlan-inter-vlan-routing/) | VLANs, 802.1Q-Trunk, Native VLAN, Router-on-a-Stick, Migration auf Layer-3-Switch (SVI) | ✅ fertig |
| 02 | OSPF Multi-Area | OSPF-Areas, Router-ID, Cost, Default Route, Troubleshooting | 🔜 geplant |
| 03 | DHCP, NAT & DNS | DHCP-Server/Relay, PAT, Static NAT, DNS | 🔜 geplant |
| 04 | ACL & Port Security | Standard/Extended ACL, Port Security, SSH, Device Hardening | 🔜 geplant |
| 05 | STP, EtherChannel & HSRP | Rapid PVST+, Root Bridge, LACP, Gateway-Redundanz | 🔜 geplant |
| 06 | IPv6 Dual-Stack | IPv6-Adressierung, SLAAC, OSPFv3 / Static | 🔜 geplant |
| Py | Python-Tools | Subnet-Rechner, Config-Generator aus CSV, Parser für `show`-Ausgaben | 🔜 geplant |

> **Hinweis zu Python:** Packet Tracer erlaubt keine direkte Verbindung über Netmiko o. Ä. Die Python-Tools arbeiten deshalb eigenständig – sie erzeugen oder analysieren Konfigurationen.

## Über mich

- Absolvent der **HTL Wien West**, Kolleg für Informatik, Schwerpunkt Systemtechnik (2026)
- Seit 2021 eigenständig verantwortlich für die IT einer Apotheke (ca. 12 Arbeitsplätze): Support, Windows-Clients, Google Workspace, Koordination mit externen Dienstleistern
- **CCNA** in Vorbereitung
- Ziel: Einstieg in Enterprise-Networking und Systemadministration in Wien

Praktische Netzwerkerfahrung habe ich bisher in Laborumgebungen gesammelt – dieses Repository zeigt, was ich dort umgesetzt und verstanden habe.

## Werkzeuge

- Cisco Packet Tracer 9.0.1
- Git / GitHub

## Kontakt

- LinkedIn: *[Link einfügen]*
