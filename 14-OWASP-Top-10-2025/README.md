# 🌐 OWASP Top 10 (Édition 2025)

Focus sur les vulnérabilités les plus critiques des applications web selon les dernières mises à jour de l'OWASP.

## 🚨 Vulnérabilités Clés Étudiées

### 1. IAAA Failures (Identification, Authentication, Authorization)
- **Problème** : Mauvaise gestion des sessions, mots de passe par défaut, ou manque d'authentification multi-facteurs (MFA).
- **Risque** : Usurpation d'identité et accès non autorisé aux comptes.

### 2. Application Design Flaws
- **Problème** : Erreurs logiques lors de la conception même de l'application (ex: absence de vérification d'un paiement côté serveur).
- **Risque** : Contournement des règles métier de l'entreprise.

### 3. Insecure Data Handling
- **Problème** : Données sensibles (mots de passe, numéros de carte) stockées ou transmises sans chiffrement adéquat.
- **Risque** : Fuite de données massives (Data Breach).

## 🛡️ Stratégies de Remédiation
- Mise en place de politiques de mots de passe fortes.
- Utilisation systématique du chiffrement TLS.
- Validation rigoureuse de toutes les entrées utilisateurs côté serveur.

## 📝 Ce que j'ai retenu
Le Web évolue vite. Maîtriser l'OWASP Top 10 version 2025 permet d'avoir une approche proactive de la sécurité. J'ai appris que la sécurité doit être intégrée dès la phase de design (**Security by Design**) plutôt que d'être ajoutée après coup comme un simple "patch".
