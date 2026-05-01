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
  john --wordlist=/usr/share/wordlists/rockyou.txt hash.txt
