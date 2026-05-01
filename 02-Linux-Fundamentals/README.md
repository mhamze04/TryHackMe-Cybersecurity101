# 🐧 Linux Fundamentals (Part 1, 2 & 3)

Ce module couvre les bases essentielles du système d'exploitation Linux, indispensable pour la navigation en ligne de commande et la gestion des serveurs en cybersécurité.

## 🛠️ Concepts Clés
- **Navigation** : Déplacement dans l'arborescence des fichiers.
- **Permissions** : Compréhension du modèle `rwx` (Read, Write, Execute) et des utilisateurs (Sudo).
- **Gestion de fichiers** : Création, lecture et modification de fichiers en CLI.
- **Recherche & Filtrage** : Utilisation de `grep`, `find` et des pipes `|`.

## 💻 Commandes Essentielles Apprises

### 1. Navigation et Système
| Commande | Description |
| :--- | :--- |
| `pwd` | Afficher le répertoire de travail actuel. |
| `ls -la` | Lister tous les fichiers (y compris cachés) avec les détails. |
| `cd /chemin` | Changer de répertoire. |
| `whoami` | Savoir quel utilisateur est actuellement connecté. |

### 2. Manipulation de fichiers
- `cat filename.txt` : Afficher le contenu d'un fichier.
- `touch newfile.txt` : Créer un nouveau fichier vide.
- `mkdir folder_name` : Créer un nouveau dossier.
- `cp` / `mv` : Copier ou déplacer des fichiers.
- `nano` ou `vim` : Édition de fichiers dans le terminal.

### 3. Permissions et Sécurité
- `chmod 700 file` : Donne les pleins pouvoirs au propriétaire seul.
- `chown user:group file` : Change le propriétaire du fichier.
- `sudo` : Exécuter une commande avec les privilèges "root".

### 4. Recherche et Analyse
- `grep "mot_clé" file.txt` : Chercher une chaine de caractères dans un fichier.
- `find / -name flag.txt` : Rechercher un fichier spécifique dans tout le système.
- `|` (Pipe) : Rediriger la sortie d'une commande vers une autre (ex: `cat file.txt | grep "admin"`).

## 📝 Ce que j'ai retenu
L'importance de la gestion des droits. En sécurité, une mauvaise configuration des permissions (ex: un fichier `/etc/shadow` lisible par tous) peut mener à une compromission totale du système.
