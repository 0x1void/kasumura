Perfect.
Here is the final README.md in pure Markdown, clean, beautiful, bilingual, emoji-enhanced, ready to paste directly into GitHub as-is.
No HTML, no extra formatting — 100% Markdown.


---

🥷✨ KASUMURA PROJECT

Domain: kasumura.clan

> Heavens hold the clan,
Kasumi's steel wall stands firm,
Homura's storm breaks.




---

🚀 Technologies & Badges

![Fedora 43](https://img.shields.io/badge/Fedora-43-294172?logo=fedora&logoColor=white)  
![openSUSE Tumbleweed (Research VM)](https://img.shields.io/badge/openSUSE_Tumbleweed-Research%20VM-73ba25?logo=opensuse&logoColor=white)  
![KVM / QEMU](https://img.shields.io/badge/KVM%20%2F%20QEMU-Virtualization-333333?logo=qemu&logoColor=white)  
![libvirt](https://img.shields.io/badge/libvirt-Enabled-4C9A2A?logo=libvirt&logoColor=white)  
![pfSense](https://img.shields.io/badge/pfSense-Firewall-1F4A7F?logo=pfsense&logoColor=white)  
![Windows Server 2025](https://img.shields.io/badge/Windows_Server-2025-0078D6?logo=windows&logoColor=white)  
![Debian (GLPI / Zabbix / Wazuh)](https://img.shields.io/badge/Debian-GLPI%20%2F%20Zabbix%20%2F%20Wazuh-A80030?logo=debian&logoColor=white)  
![TrueNAS CORE](https://img.shields.io/badge/TrueNAS-CORE-0B6AA2?logo=truenas&logoColor=white)  
![Pi-hole](https://img.shields.io/badge/Pi--hole-DNS%20Filtering-A41F1F?logo=pi-hole&logoColor=white)  
![Headscale](https://img.shields.io/badge/Headscale-Identity%20Overlay-444444?logo=tailscale&logoColor=white)  
![License: MIT](https://img.shields.io/badge/License-MIT-FFC107?logo=open-source-initiative&logoColor=black)


---

🇺🇸 ENGLISH SECTION

🌸 1. Introduction

KasuMura is a fully segmented Zero-Trust cyber lab, built around the duality of two legendary forces:

Kasumi 🌫️ — The Mist Princess
Protector, guardian, identity keeper — the silent shield of the clan.

Homura 🔥 — The Crimson Storm
Attacker, counter-attacker, relentless flame against threats.


Together, they form a balanced environment of defensive and offensive cybersecurity.


---

🏯 2. Architecture Overview

KasuMura’s network is divided into four domains:

Zone	Purpose

🌫️ CoreNet	Identity, AD, DNS, pfSense, core security
🔥 OpsNet	Monitoring, SIEM, analytics, GLPI
🧊 ClientNet	Storage, clients, shares
⚡ Tailnet	Zero-trust remote access (Headscale)



---

🖥️ 3. Professional Naming Convention

Kasumi Prefix (Defense)

kdc-kasumi — Domain Controller
idp-kasumi — Headscale + Pi-hole
mon-kasumi — Zabbix monitoring
itsm-kasumi — GLPI
hv-kasumi — Fedora Hypervisor

Homura Prefix (Offense)

fw-homura — pfSense firewall
siem-homura — Wazuh SIEM
ids-homura — IDS/IPS
nas-homura — TrueNAS
red-homura-01 — Offensive VM


---

📦 4. VM & Service Inventory

FQDN	Role	IP	Zone

kdc-kasumi.kasumura.clan	AD + DNS	10.10.10.10	CoreNet
fw-homura.kasumura.clan	pfSense	10.10.10.1	CoreNet
idp-kasumi.kasumura.clan	Headscale + Pi-hole	10.10.10.2	CoreNet
mon-kasumi.kasumura.clan	Zabbix	10.20.20.20	OpsNet
siem-homura.kasumura.clan	Wazuh SIEM	10.20.20.30	OpsNet
itsm-kasumi.kasumura.clan	GLPI	10.20.20.40	OpsNet
nas-homura.kasumura.clan	TrueNAS Vault	10.30.30.20	ClientNet
red-homura-01.kasumura.clan	Kali / Red Team	10.20.20.50	OpsNet



---

🌐 5. Domain & DNS Structure

Internal domain: kasumura.clan

Organized by network segments:

*.corenet.kasumura.clan

*.opsnet.kasumura.clan

*.clientnet.kasumura.clan

*.tailnet.kasumura.clan




---

🗺️ 6. Network Diagram




---

🧩 7. Deployment Summary

Install Fedora 43 hypervisor

Configure libvirt bridges + VLANs

Deploy pfSense (fw-homura)

Configure AD/DNS (kdc-kasumi)

Install Headscale + Pi-hole (idp-kasumi)

Deploy Zabbix, Wazuh, GLPI

Configure TrueNAS (nas-homura)

Apply Zero-Trust firewalling



---

✔️ 8. Validation Checklist

[ ] Admin access only via Tailnet

[ ] DNS functional across VLANs

[ ] Wazuh receiving logs

[ ] Zabbix agents reporting

[ ] SMB encryption enforced

[ ] VLAN isolation validated

[ ] ZFS snapshots healthy



---

📜 9. License

MIT License — Open & permissive.


---

✉️ 10. Contact

Raiden Jaafar
📧 r01ai@proton.me
🐙 GitHub: R01ai
📍 Levallois-Perret, France


---

🔥🌫️ KasuMura — where the shield meets the flame.

---

🇫🇷 SECTION FRANÇAISE

🌸 1. Introduction

KasuMura est un laboratoire Zero-Trust divisé entre :

Kasumi 🌫️ — La Princesse de la Brume
Défense, identité, protection du clan.

Homura 🔥 — La Tempête Écarlate
Attaque, contre-attaque, recherche offensive.



---

🏯 2. Vue d’ensemble de l’architecture

Zone	Rôle

🌫️ CoreNet	AD, DNS, pfSense, services essentiels
🔥 OpsNet	SIEM, supervision, ITSM
🧊 ClientNet	Stockage, clients
⚡ Tailnet	Accès Zero-Trust (Headscale)



---

🖥️ 3. Convention de nommage professionnel

Kasumi (Défense)

kdc-kasumi, idp-kasumi, mon-kasumi, itsm-kasumi, hv-kasumi

Homura (Offense)

fw-homura, siem-homura, ids-homura, nas-homura, red-homura-01


---

📦 4. Tableau des systèmes

(identique à la section EN, même IPs & rôles)


---

🌐 5. Domaine & DNS

Domaine interne : kasumura.clan

Zones structurées selon les VLANs



---

🗺️ 6. Diagramme

![Network Architecture](sentryx_architecture.png)


---

🧩 7. Déploiement

Hyperviseur Fedora 43

VLANs + bridges

pfSense (fw-homura)

AD/DNS (kdc-kasumi)

Headscale + Pi-hole

Zabbix, Wazuh, GLPI

TrueNAS

Règles Zero-Trust



---

✔️ 8. Checklist

Accès admin via Tailnet

DNS OK

SIEM OK

Supervision OK

SMB chiffré

Isolation VLAN

Snapshots ZFS OK



---

📜 9. Licence

MIT.


---

✉️ 10. Contact

Raiden Jaafar
📧 r01ai@proton.me
🐙 GitHub : R01ai


---

🔥🌫️ KasuMura — là où le bouclier rencontre la flamme.
