# 🛠️ Offensive Security Tooling

Ce module est dédié à l'automatisation de la reconnaissance, du brute-force et de l'exploitation à l'aide des outils les plus reconnus du domaine.

## 🧰 Boîte à outils

### 1. Gobuster
Utilisé pour la découverte de contenu (énumération de répertoires et sous-domaines).
- **Objectif** : Trouver des pages cachées (ex: `/admin`, `/config`, `/.env`).
- **Commande** : 
  ```bash
  gobuster dir -u http://<IP_CIBLE> -w /usr/share/wordlists/dirb/common.txt 
### 2. Hydra
L'outil de référence pour le brute-force de protocoles (SSH, FTP, HTTP-POST-FORM).

- **Objectif**  : Tester des listes d'identifiants contre un service.

- **Commande** (SSH) :

```Bash
  hydra -l admin -P /usr/share/wordlists/rockyou.txt <IP_CIBLE> ssh
```
### 3. SQLMap
Automatisation complète de la détection et de l'exploitation d'injections SQL.

- **Objectif** : Extraire des bases de données entières sans écrire de scripts manuels.

- **Commande** :

```Bash
sqlmap -u "[http://target.com/page.php?id=1](http://target.com/page.php?id=1)" --dbs
```
### 4. Shells Overview
Compréhension des différents types d'accès à distance :

- **Reverse Shell** : La cible se connecte à l'attaquant (préféré pour contourner les pare-feu).

- **Bind Shell** : L'attaquant se connecte directement à un port ouvert sur la cible.

- **Netcat (nc)** : L'outil "couteau suisse" pour créer des connexions.

## 📝 Ce que j'ai retenu
L'automatisation est puissante mais doit être utilisée avec discernement. Un outil comme sqlmap peut être très bruyant et facilement détecté par un IDS (Intrusion Detection System). Savoir configurer ces outils (choix des wordlists, gestion des threads) est aussi important que de savoir les lancer.
