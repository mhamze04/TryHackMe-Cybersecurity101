# 🛡️ Defensive Security Fundamentals

Ce module introduit les concepts clés de la protection des actifs numériques, de la surveillance des systèmes et de la réponse aux incidents.

## 🏢 Organisation de la Défense
- **SOC (Security Operations Center)** : Le centre de commande où les analystes surveillent les alertes de sécurité 24/7.
- **Incident Response (IR)** : La méthodologie suivie pour contenir, éradiquer et se remettre d'une cyberattaque.
- **Digital Forensics (DF)** : L'art de collecter et d'analyser des preuves numériques pour comprendre le "quoi, comment et qui" d'une intrusion.

## 🔍 Analyse et Détection
- **Log Fundamentals** : Apprentissage de l'importance des journaux d'événements (Windows Event Logs, Syslog sous Linux) pour retracer les actions d'un attaquant.
- **Analyse de fichiers** : Identification de fichiers malveillants via leurs hashs ou leur comportement.

## 🛠️ Méthodologies de Réponse
L'accent est mis sur le cycle de vie d'un incident :
1. **Préparation** : Durcissement des systèmes.
2. **Identification** : Détecter l'anomalie dans les logs.
3. **Confinement** : Isoler la machine compromise du réseau.
4. **Éradication/Recouvrement** : Nettoyer le système et restaurer les services.

## 📝 Ce que j'ai retenu
La défense est une course contre la montre. J'ai appris que l'attaquant doit réussir toutes ses étapes pour parvenir à ses fins, alors que le défenseur n'a besoin de détecter qu'une seule étape (via les logs ou une alerte réseau) pour stopper l'intrusion. La visibilité (avoir les bons logs au bon endroit) est la base de toute stratégie défensive.
