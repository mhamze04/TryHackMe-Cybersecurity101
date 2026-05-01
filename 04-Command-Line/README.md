# 💻 Command Line Mastery: Windows & Linux

Ce module se concentre sur l'utilisation avancée des interfaces en ligne de commande (CLI) pour l'administration système et l'automatisation.

## 🛠️ Environnements Étudiés
- **Windows Command Prompt (CMD)** : L'interface classique pour les tâches système de base.
- **Windows PowerShell** : Un shell puissant basé sur des objets, essentiel pour l'automatisation Windows.
- **Linux Shells (Bash/Zsh)** : Les standards pour la gestion des systèmes Unix et l'écriture de scripts.

## ⌨️ Commandes Comparatives

| Action | Windows (CMD) | PowerShell | Linux (Bash) |
| :--- | :--- | :--- | :--- |
| Lister les fichiers | `dir` | `Get-ChildItem` (ou `ls`) | `ls` |
| Voir le contenu | `type` | `Get-Content` (ou `cat`) | `cat` |
| IP Config | `ipconfig` | `Get-NetIPAddress` | `ip addr` ou `ifconfig` |
| Processus actifs | `tasklist` | `Get-Process` | `ps aux` ou `top` |

## 🚀 Focus sur PowerShell
PowerShell ne manipule pas seulement du texte, mais des **objets**. 
- **Pipeline (`|`)** : Permet de passer un objet entier à la commande suivante.
- **Filtrage** : `Get-Service | Where-Object {$_.Status -eq "Running"}` (Affiche uniquement les services actifs).

## 🐚 Linux Shells & Scripting
- **Shebang (`#!/bin/bash`)** : Indique au système quel interpréteur utiliser pour le script.
- **Variables** : Utilisation de `$VAR` pour stocker des données.
- **Permissions d'exécution** : Nécessité de faire un `chmod +x script.sh` pour rendre un script utilisable.

## 📝 Ce que j'ai retenu
La ligne de commande est l'outil le plus puissant d'un analyste cyber. PowerShell est particulièrement redoutable pour l'énumération post-exploitation dans un environnement Windows, tandis que la maîtrise du Bash est indispensable pour l'analyse de logs sous Linux.
