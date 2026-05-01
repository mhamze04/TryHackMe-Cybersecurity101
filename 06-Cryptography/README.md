# 🔐 Cryptography & Password Cracking

Ce module traite des principes du chiffrement, de l'utilisation des fonctions de hachage et des techniques de récupération de mots de passe.

## 🛠️ Concepts Fondamentaux
- **Chiffrement Symétrique** : Une seule clé pour chiffrer et déchiffrer (ex: AES). Rapide mais pose le problème du partage de la clé.
- **Chiffrement Asymétrique (Public Key)** : Une clé publique pour chiffrer, une clé privée pour déchiffrer (ex: RSA). Base de la sécurité sur Internet (HTTPS/SSH).
- **Hashing (Hachage)** : Transformation irréversible d'une donnée en une empreinte unique (ex: MD5, SHA-256). Utilisé pour vérifier l'intégrité et stocker les mots de passe.

## 🔨 Outils et Pratique

### 1. John the Ripper
Un outil puissant pour casser les mots de passe (cracking).
- **Attaque par dictionnaire** : Tester une liste de mots courants (ex: `rockyou.txt`).
- **Commande type** : 
  ```
  john --wordlist=/usr/share/wordlists/rockyou.txt hash.txt ```
  
### 2. Identification de Hash
Avant de casser un hash, il faut savoir de quel type il s'agit.

Utilisation d'outils comme hash-identifier ou des services en ligne pour distinguer un MD5 d'un SHA-1.

🛡️ Pourquoi le Hachage est crucial ?
En cybersécurité, on ne stocke jamais un mot de passe en "clair" dans une base de données. On stocke son hash. Si la base de données est volée, l'attaquant n'a que les empreintes et doit utiliser des outils comme John the Ripper ou Hashcat pour retrouver les originaux.

## 📝 Ce que j'ai retenu
La différence entre chiffrer (réversible) et hacher (non réversible). 
J'ai également appris que la force d'un mot de passe ne dépend pas seulement de sa complexité, mais aussi de la robustesse de l'algorithme de hachage utilisé (ex: préférer Argon2 ou Bcrypt à MD5).
