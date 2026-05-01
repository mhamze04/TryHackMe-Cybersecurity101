# 🌐 Web Hacking Fundamentals

Ce module explore les vulnérabilités courantes des applications web et l'utilisation d'outils d'interception pour manipuler le trafic.

## 🛠️ Concepts & Langages
- **Web Application Basics** : Compréhension du modèle Client-Serveur et du protocole HTTP (Requêtes/Réponses).
- **JavaScript Essentials** : Utilisation de JS côté client et risques associés (XSS).
- **SQL Fundamentals** : Bases du langage SQL pour comprendre comment les données sont extraites des bases de données.

## 🛡️ Outils Majeurs

### Burp Suite : Le Proxy d'Interception
Burp Suite est l'outil incontournable pour tester la sécurité web.
- **Proxy/Intercept** : Permet de stopper une requête HTTP avant qu'elle n'atteigne le serveur pour la modifier.
- **Repeater** : Permet de renvoyer plusieurs fois la même requête en modifiant les paramètres pour tester des injections.
- **Intruder** : Utilisé pour automatiser des attaques (ex: brute-force de formulaires).

## 🔍 Vulnérabilités Étudiées
- **Injection SQL (SQLi)** : Manipuler une requête SQL via un champ de saisie pour voler des données.
- **Authentification** : Faiblesses dans les formulaires de connexion (mots de passe faibles, absence de limitation de tentatives).
- **IDOR** : Accès non autorisé à des ressources en modifiant simplement un identifiant dans l'URL.

## 💻 Exemple de test (Logique)
1. Activer le mode **Intercept** dans Burp.
2. Envoyer un identifiant `' OR 1=1 --` dans un champ de login.
3. Analyser si le serveur renvoie une erreur ou connecte l'utilisateur (Indicateur de SQLi).

## 📝 Ce que j'ai retenu
La sécurité web repose sur une règle d'or : **"Ne jamais faire confiance aux entrées de l'utilisateur"**. Burp Suite est l'outil qui m'a permis de comprendre concrètement comment un attaquant "voit" et manipule les données entre son navigateur et le serveur.
