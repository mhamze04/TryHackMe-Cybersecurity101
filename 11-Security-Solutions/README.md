# 🏗️ Security Solutions: SIEM, IDS & Firewalls

Ce module présente les solutions technologiques utilisées par les entreprises pour protéger leur infrastructure, détecter les menaces et gérer les vulnérabilités de manière centralisée.

## 🛡️ Solutions de Protection et Détection

### 1. SIEM (Security Information and Event Management)
Le SIEM est le cerveau du SOC. Il agrège les logs de toutes les sources (serveurs, pare-feu, applications).
- **Fonctionnement** : Corrélation d'événements en temps réel pour générer des alertes de sécurité.
- **Exemple** : Si 50 échecs de connexion surviennent en 1 minute sur un serveur, le SIEM déclenche une alerte "Brute-force".

### 2. Firewall (Pare-feu)
La première ligne de défense périmétrique.
- **Rôle** : Filtrer le trafic entrant et sortant selon des règles de sécurité (IP, ports, protocoles).
- **Concepts** : Différence entre le filtrage par état (Stateful) et le filtrage applicatif (Next-Gen Firewall).

### 3. IDS/IPS (Intrusion Detection & Prevention System)
- **IDS** : Surveille le trafic réseau et alerte en cas d'activité suspecte (ex: Snort).
- **IPS** : Agit activement pour bloquer le trafic malveillant identifié.

### 4. Vulnerability Scanners
Outils automatisés (ex: Nessus, OpenVAS) qui scannent le réseau à la recherche de logiciels non mis à jour ou de configurations dangereuses.

## 📝 Ce que j'ai retenu
Une défense efficace repose sur la **Défense en Profondeur**. Aucun outil n'est parfait : le Firewall bloque les accès non autorisés, l'IDS détecte les attaques qui passent à travers, et le SIEM donne la visibilité globale. Le scan de vulnérabilité régulier permet d'anticiper les attaques en corrigeant les failles avant qu'elles ne soient exploitées.
