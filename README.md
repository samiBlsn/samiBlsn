# Sami Boulsnane — Analyste Cybersécurité | SOC / Blue Team

🎓 Diplômé d'un **Master MIAGE — Sécurité des Systèmes d'Information et Réseaux**  
🛡️ Orientation : **SOC, Blue Team, Detection Engineering, Incident Response**  
📍 Strasbourg — Mobile France entière  
✅ Disponible immédiatement

---

## 👋 À propos

Je suis diplômé d'un Master MIAGE spécialisé en sécurité des systèmes d'information et des réseaux et je souhaite évoluer vers des fonctions de **SOC, Blue Team et cybersécurité opérationnelle**.

Lors de mon stage de fin d'études au **Product Security Operations Center de Stellantis**, j'ai déployé et configuré une plateforme de **Breach & Attack Simulation basée sur OpenBAS** sous Linux, Docker et AWS EC2.

J'ai notamment travaillé sur :

- le déploiement et la configuration de la plateforme ;
- la création de scénarios d'attaque ;
- l'utilisation de l'Automotive Threat Matrix ;
- la documentation technique ;
- la présentation de la solution auprès d'équipes ICT.

En parallèle, je construis des laboratoires personnels afin de pratiquer la **détection, l'investigation, l'analyse de logs et l'automatisation SOC**.

---

## 🛠️ Compétences techniques

### SIEM / SOC / Détection

![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3AABF5?style=flat&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic_Stack-005571?style=flat&logo=elastic&logoColor=white)
![Sysmon](https://img.shields.io/badge/Sysmon-5C2D91?style=flat&logo=windows&logoColor=white)

**Pratique :** Microsoft Sentinel, Wazuh, Sysmon, KQL, journaux Windows, investigation, threat hunting, corrélation d'événements  
**Formation :** Splunk, Elastic Stack, Defender XDR

### Réseau

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-CC0000?style=flat&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat&logoColor=white)

MITRE ATT&CK · Cyber Kill Chain · CVE/CVSS · IOC · Wireshark · Snort · Nmap

### Cloud / Infrastructure

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat&logo=vmware&logoColor=white)

Windows Server · Active Directory · Linux · VMware · Docker · AWS EC2 · Microsoft Azure · TCP/IP · DNS · TLS · Nginx · proxys · pare-feu

### Scripting / Développement

![KQL](https://img.shields.io/badge/KQL-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

Python · Bash · PowerShell · Java · JavaScript


---

# 🚀 Projets principaux

## 🔬 [SOC Home Lab — Wazuh / Sysmon / Active Directory](https://github.com/samiBlsn/SOC-HomeLab)

Environnement SOC complet déployé sous VMware avec **Wazuh**, **Active Directory**, **Sysmon**, des endpoints Windows/Linux et une machine Kali.

Le laboratoire couvre notamment :

- déploiement d'un domaine Active Directory ;
- collecte des événements Windows et Linux ;
- enrichissement de la télémétrie avec Sysmon ;
- création de règles de détection personnalisées dans Wazuh ;
- mapping MITRE ATT&CK ;
- simulations d'attaques ;
- corrélation d'alertes ;
- investigation et rapport d'incident.

Exemples de détections développées :

```text
T1003.001 — Credential Dumping / LSASS
T1550.002 — Pass-the-Hash
T1110.001 — Brute Force
T1136.001 — Account Creation
T1059.001 — PowerShell
T1490 — Inhibit System Recovery
```

Kill chain simulée :

```text
Brute Force
    ↓
Credential Dumping
    ↓
Pass-the-Hash
    ↓
Persistence
    ↓
PowerShell Obfuscation
    ↓
Inhibit System Recovery
```

Le projet inclut également un **rapport d'investigation complet** avec timeline, IoCs, analyse MITRE ATT&CK, gestion des faux positifs et recommandations de remédiation.

---

## ☁️ [Microsoft Sentinel — Mass Deletion Detection Lab](https://github.com/samiBlsn/sentinel-mass-deletion-lab)

Laboratoire **Detection Engineering / SOAR** réalisé avec Microsoft Sentinel autour d'un scénario de suppression massive de groupes de ressources Azure.

Le laboratoire couvre notamment :

- analyse de la table `AzureActivity` ;
- développement de requêtes KQL ;
- threat hunting ;
- comparaison avec une baseline historique ;
- création d'une Scheduled Analytics Rule ;
- Entity Mapping ;
- Custom Details ;
- mapping MITRE ATT&CK ;
- génération et investigation d'un incident ;
- automatisation avec Azure Logic Apps.

Technique détectée :

```text
T1485 — Data Destruction
```

Workflow :

```text
Azure Activity Log
        ↓
Threat Hunting KQL
        ↓
Scheduled Analytics Rule
        ↓
Incident High
        ↓
Investigation
        ↓
Automation Rule
        ↓
Logic Apps Playbook
```

Résultat du scénario :

```text
6 suppressions de groupes de ressources
        ↓
Détection automatique
        ↓
Incident Microsoft Sentinel
        ↓
Investigation
        ↓
Enrichissement automatique
```

---

## 💼 Expérience cybersécurité

### Product Security Operations Center — Stellantis

Stage de fin d'études orienté cybersécurité produit :

- déploiement d'**OpenBAS** ;
- Linux / Docker / AWS EC2 ;
- configuration de la plateforme ;
- scénarios de Breach & Attack Simulation ;
- Automotive Threat Matrix ;
- documentation technique ;
- présentation de la solution auprès d'équipes ICT.

---

## 📜 Certifications & formation

| Certification / formation | Statut |
|---|---|
| **Microsoft Certified: Security Operations Analyst Associate — SC-200** | Obtenue — Octobre 2026 |
| **TryHackMe Security Analyst Level 1** | Complété — 2026 |

---

## 🎯 Objectif professionnel

Je recherche principalement un poste junior de :

```text
Analyste SOC
Analyste CSIRT
Analyste Cybersécurité
Detection Engineer junior
```

Je suis particulièrement intéressé par :

- l'analyse et la qualification d'incidents ;
- l'investigation ;
- le threat hunting ;
- l'amélioration des règles de détection ;
- l'analyse de logs ;
- l'automatisation SOC ;
- la sécurité Windows, Active Directory et Azure.

---

## 🧭 Prochains projets

- approfondissement du SOC Home Lab ;
- nouveaux scénarios Wazuh / Sysmon ;
- projet dédié à l'audit de sécurité Active Directory ;

---

## 📬 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sami_Boulsnane-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sami-boulsnane-510685271/)
[![Email](https://img.shields.io/badge/Email-boulsnane.sami%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:boulsnane.sami@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Samim68-212C42?style=flat&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Samim68)
