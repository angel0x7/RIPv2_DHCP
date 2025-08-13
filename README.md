# TP Packet Tracer — RIPv2 & DHCP
**Auteur** : Velasco Angel  
**Outil** : Cisco Packet Tracer  

---

## Introduction
Ce dépôt présente deux travaux pratiques réalisés sous **Cisco Packet Tracer** :  
1. La configuration du **routage dynamique RIPv2**.  
2. La mise en place d’un **service DHCP** (intégré sur routeur et serveur autonome).  

Ces TP illustrent des concepts fondamentaux en administration réseau et s’accompagnent de rapports, présentations et fichiers Packet Tracer pour reproduire la configuration.

---

## Contenu du dépôt
- **Rapports**
  - [RIPv2_Velasco_.docx](RIPv2_Velasco_.docx)  
  - [DHCP_Server_Velasco Angel.docx](DHCP_Server_Velasco%20Angel.docx)
- **Présentations** 
  - RIPv2 : Packet Tracer - Configuring RIPv2.pdf
  - DHCP : Lab 02_FR-v3.pdf
- **Fichiers Packet Tracer**
  - `Packet Tracer - Configuring RIPv2-v1.pkt`
  - `Velasco_DHCP_Server_V1.pkt`
  - `Velasco_DHCP_Server_V2.pkt`

---

## Résumé des TP

### 🔹 TP 1 — RIPv2
**Objectif** : Assurer la connectivité entre plusieurs réseaux via un routage dynamique.  
**Actions principales** :
- Activation de RIPv2 (`router rip`, `version 2`, `no auto-summary`).
- Annonce des réseaux directement connectés (`network <adresse>`).
- Vérification : `show ip route`, `ping`.

**Résultat** : Routes apprises automatiquement et communication possible entre tous les hôtes.

---

### 🔹 TP 2 — DHCP
**Objectif** : Automatiser l’attribution d’adresses IP sur différents réseaux.  
**Actions principales** :
- Configuration d’un **serveur DHCP intégré** sur routeur (`ip dhcp pool`, exclusions, DNS, gateway).
- Mise en place d’un **serveur DHCP autonome** avec `ip helper-address` pour le relais.
- Vérification : `ipconfig`, `show ip dhcp binding`, `ping`, `traceroute`.

**Résultat** : Attribution dynamique d’IP fonctionnelle sur plusieurs sous-réseaux.

---

## Conclusion
Ces TP démontrent la mise en œuvre pratique de **RIPv2** et **DHCP** dans un environnement simulé.  
- **RIPv2** simplifie la gestion des routes dans un réseau étendu.  
- **DHCP** centralise et automatise la configuration IP des clients, même sur des réseaux distants.  

Les documents et fichiers fournis permettent de reproduire facilement les configurations et de comprendre le fonctionnement de ces services.
