# 🪟 Windows & Active Directory Fundamentals

Ce module explore l'administration Windows du point de vue de la sécurité et les bases du fonctionnement d'un domaine Active Directory.

## 🛠️ Concepts Clés
- **Système de fichiers NTFS** : Gestion des permissions et des droits d'accès.
- **Registre Windows** : Base de données de configuration du système (souvent ciblée pour la persistance).
- **UAC (User Account Control)** : Mécanisme de protection contre les modifications non autorisées.
- **Active Directory (AD)** : Service d'annuaire pour gérer les utilisateurs, ordinateurs et permissions à grande échelle.

## 🔑 Composants d'Active Directory
| Composant | Description |
| :--- | :--- |
| **Domain Controller (DC)** | Le serveur qui gère les requêtes d'authentification. |
| **Forest** | Le plus haut niveau d'organisation (regroupe plusieurs domaines). |
| **OU (Organizational Unit)** | Utilisé pour organiser les objets et appliquer des GPO. |
| **GPO (Group Policy Object)** | Règles de configuration appliquées aux utilisateurs/machines. |

## 🛡️ Sécurité Windows
- **Authentification** : Différence entre NTLM et Kerberos (le protocole par défaut de l'AD).
- **Privilèges** : Distinction entre un utilisateur standard et un Administrateur du Domaine (Domain Admin).

## 📝 Ce que j'ai retenu
La puissance d'Active Directory réside dans la centralisation, mais c'est aussi un point de défaillance unique : si le **Domain Controller** est compromis, tout le réseau l'est. La compréhension des GPO est essentielle pour durcir (hardening) un environnement Windows.
