# 🛠️ Defensive Security Tooling

Ce module se concentre sur les outils spécialisés pour l'analyse de données, le reverse engineering de base et l'analyse de logiciels malveillants (malware).

## 🧪 Analyse et Manipulation de Données

### 1. CyberChef
Surnommé le "couteau suisse du cyber", cet outil permet de manipuler les données facilement.
- **Utilisation** : Décodage (Base64, Hex), conversion de formats, déchiffrement simple et extraction de chaînes de caractères.
- **Compétence** : Savoir automatiser une "recette" pour nettoyer des données brutes ou obfusquées.

### 2. CAPA
Outil de détection de capacités dans les fichiers exécutables.
- **Rôle** : Identifier ce qu'un programme tente de faire (ex: "ouvrir une connexion réseau", "modifier le registre") sans exécuter le fichier.

## 🖥️ Environnements d'Analyse (Sandboxing)

### 1. REMnux
Une distribution Linux spécialisée dans l'ingénierie inverse et l'analyse de malwares.
- **Usage** : Analyse statique et dynamique de fichiers suspects dans un environnement isolé.

### 2. FlareVM
Une distribution basée sur Windows (via un script de modification) conçue pour l'analyse de logiciels malveillants sur Windows.
- **Arsenal** : Contient des débogueurs, des désassembleurs et des outils d'analyse réseau.

## 📝 Ce que j'ai retenu
L'analyse défensive demande de la rigueur et l'utilisation d'environnements isolés (VM) pour éviter toute contamination. Des outils comme CyberChef font gagner un temps précieux lors de l'investigation initiale, tandis que FlareVM et REMnux fournissent les laboratoires nécessaires pour disséquer des menaces complexes.
