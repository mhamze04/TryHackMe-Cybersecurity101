# 🌐 Networking Essentials & Security Tools

Ce module couvre les fondements des réseaux informatiques, les protocoles de communication et les outils indispensables pour l'analyse de trafic et le scan de vulnérabilités.

## 📡 Concepts de base
- **Modèle OSI** : Compréhension des 7 couches (Physique à Application).
- **Modèle TCP/IP** : Le standard d'Internet.
- **Protocoles Clés** :
    - **Insecure** : HTTP (80), FTP (21), Telnet (23).
    - **Secure** : HTTPS (443), SSH (22), SFTP (22).
    - **Core** : DNS (53), DHCP (67/68), ICMP (Ping).

## 🛠️ Outils d'Analyse et de Scan

### 1. Nmap (Network Mapper)
Utilisé pour la reconnaissance et l'énumération des ports.
- `$ nmap -sV <IP>` : Détecte les versions des services ouverts.
- `$ nmap -O <IP>` : Tente d'identifier le système d'exploitation.
- `$ nmap -sC <IP>` : Exécute les scripts par défaut (NSE) pour détecter des vulnérabilités simples.

### 2. Wireshark & Tcpdump
Analyse de paquets pour comprendre ce qui transite sur le réseau.
- **Wireshark** : Interface graphique permettant d'analyser des fichiers `.pcap`. Utilisation de filtres (ex: `http.request.method == "POST"`).
- **Tcpdump** : Analyseur en ligne de commande. 
    - Commande : `$ tcpdump -i eth0` (Capture le trafic sur l'interface eth0).

## 🛡️ Protocoles Sécurisés
Apprentissage de la différence entre le texte clair et le chiffrement (SSL/TLS). L'importance de SSH pour l'administration à distance sécurisée par rapport à Telnet.

## 📝 Ce que j'ai retenu
Le réseau est le vecteur d'attaque numéro 1. Sans une compréhension parfaite du "3-way handshake" TCP et du fonctionnement du DNS, il est impossible de comprendre les attaques de type Man-in-the-Middle (MitM) ou l'exfiltration de données.
