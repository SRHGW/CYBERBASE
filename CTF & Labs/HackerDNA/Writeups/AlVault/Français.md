# Compte rendu détaillé — Lab AlVault (HackerDNA)

> **Lab :** AlVault — HackerDNA  
> **Catégorie :** Web / Linux  
> **Difficulté :** Medium  
> **Récompense :** 400 XP  
> **Flags :** 2 (User et Root)  
> **Durée d'instance :** 30 minutes  

🔗 **Liens officiels :**
- [Page du lab](https://hackerdna.com/labs/alvault)
- [Mode guidé](https://hackerdna.com/labs/alvault/guided)
- [Solution](https://hackerdna.com/labs/alvault/solution)

---

## 1. Présentation générale

AlVault est un laboratoire de cybersécurité offensive proposé par HackerDNA. Il consiste à explorer une machine Linux volontairement vulnérable, identifier les faiblesses de son système et progresser jusqu'à obtenir les privilèges administrateur.

Le laboratoire met en pratique une démarche structurée de test d'intrusion : reconnaissance, énumération, obtention d'un accès initial, élévation de privilèges et validation par la récupération de flags.

## 2. Objectifs

- **Flag User :** obtenir un premier accès utilisateur à la machine.
- **Flag Root :** exploiter une faiblesse supplémentaire afin d'obtenir les privilèges `root`.

L'objectif pédagogique est de comprendre comment une reconnaissance méthodique peut conduire à la compromission complète d'un système Linux.

## 3. Méthodologie d'exploitation

### Étape 1 — Reconnaissance réseau

Identifier les ports ouverts et les services disponibles sur la machine cible.

```bash
nmap -sC -sV -p- IP_CIBLE
