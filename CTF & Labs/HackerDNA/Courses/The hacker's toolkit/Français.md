# La boîte à outils du hacker

**Formation :** Initiation au hacking  
**Plateforme :** HackerDNA Course  
**Chapitre :** 9 / 10

## Introduction

Le hacker de cinéma avec une centaine de fenêtres de texte vert est un mythe. Les vrais hackers maîtrisent un petit ensemble d'outils fiables.

Les outils utilisés par les hackers sont publics, gratuits, bien documentés et également utilisés par les professionnels de la cybersécurité.

Ce qui distingue un professionnel d'un débutant n'est pas le nombre d'outils possédés, mais la compréhension de leur fonctionnement et de leur utilité.

## Objectifs du chapitre

- Reconnaître les principales catégories d'outils de hacking.
- Comprendre le rôle des outils célèbres.
- Reconnaître leurs sorties.
- Associer un outil à une tâche.
- Comprendre leur utilisation offensive et défensive.
- Savoir quoi apprendre en premier.

## 1. Reconnaître les outils

### Exemple 1 : Une liste de ports ouverts

    PORT     STATE  SERVICE
    22/tcp   open   ssh
    80/tcp   open   http
    443/tcp  open   https
    3306/tcp closed mysql

Cette sortie correspond à un scan de ports.

**Outil : Nmap**

Nmap permet de découvrir les ports ouverts et les services associés à une machine.

### Exemple 2 : Un mot de passe cassé

    5f4dcc3b5aa765d61d8327deb882cf99:password
    Status...........: Cracked
    Recovered........: 1/1 (100.00%) Digests

Cette sortie montre un hash accompagné de son texte en clair.

**Outil : Hashcat**

Hashcat permet de tester des candidats de mots de passe contre des hashes.

Le hash MD5 présenté correspond au mot de passe `password`.

### Exemple 3 : Une requête HTTP capturée

    POST /login HTTP/1.1
    Host: <target>
    Content-Type: application/x-www-form-urlencoded

    username=admin&password=guess123

Cette sortie représente une requête HTTP capturée.

**Outil : Proxy d'interception**

Un proxy d'interception permet de capturer, lire et modifier les requêtes web.

## 2. La boîte à outils et ses fonctions

| Étape | Outil | Fonction |
|---|---|---|
| Reconnaissance réseau | Nmap | Trouver les ports et services ouverts |
| Reconnaissance Internet | Shodan | Rechercher des appareils exposés |
| Analyse du trafic | Wireshark | Lire les paquets réseau |
| Hacking web | Proxy d'interception | Capturer et modifier les requêtes |
| Cassage de mots de passe | Hashcat / John the Ripper | Tester des mots de passe contre des hashes |
| Exploitation | Framework d'exploitation | Lancer et gérer des exploits |
| Base | Navigateur + terminal | Environnement de travail principal |

## 3. Les outils célèbres

### Nmap

- Scanne les réseaux.
- Identifie les ports ouverts.
- Détecte les services présents.
- Utilisé pour la reconnaissance réseau.

### Wireshark

- Capture le trafic réseau.
- Analyse les paquets.
- Permet d'observer ce qui circule sur le réseau.

### Proxy d'interception

- Se place entre le navigateur et le site.
- Capture les requêtes HTTP.
- Permet de lire et modifier les requêtes.

Exemples :
- Burp Suite
- OWASP ZAP

### Hashcat et John the Ripper

- Testent des candidats de mots de passe.
- Travaillent sur des hashes.
- Permettent d'effectuer du cassage de mots de passe.

### Framework d'exploitation

Exemple : Metasploit.

- Regroupe des exploits connus.
- Facilite leur lancement et leur gestion.
- Permet de travailler de manière structurée.

## 4. Les outils sont à double usage

Un outil n'est pas intrinsèquement offensif ou défensif.

- Nmap peut cartographier un réseau attaqué ou un réseau administré.
- Wireshark peut dépanner une connexion ou analyser un trafic suspect.
- Les proxies peuvent tester la sécurité d'une application web.
- Les frameworks peuvent être utilisés lors de tests de sécurité autorisés.

Les mêmes compétences permettent de découvrir des vulnérabilités et de les corriger.

## 5. Apprendre les outils dans le bon ordre

Le moyen le plus rapide d'apprendre un outil consiste à comprendre d'abord le problème qu'il résout.

Exemples :

- Comprendre les ports avant d'apprendre Nmap.
- Comprendre les hashes avant d'apprendre Hashcat.
- Comprendre HTTP avant d'utiliser un proxy d'interception.

Un outil devient beaucoup plus compréhensible lorsque sa fonction est connue.

## 6. Pièges courants

### Collectionner les outils au lieu des compétences

Installer de nombreux outils ne signifie pas savoir les utiliser.

Un outil maîtrisé vaut mieux que dix outils simplement connus de nom.

### Lancer un outil sans comprendre sa commande

Copier des commandes trouvées sur Internet sans les comprendre peut provoquer des erreurs ou des accidents.

Il faut comprendre ce que fait une commande avant de l'exécuter.

### Croire qu'une configuration spéciale est nécessaire

Il n'est pas nécessaire d'avoir un système d'exploitation spécialisé ou un matériel coûteux pour commencer.

Les concepts et les compétences sont plus importants que la configuration.

### Utiliser des outils contre des cibles non autorisées

Un scan ou un exploit contre un système sans autorisation peut poser des problèmes juridiques.

Il faut s'entraîner sur :
- Ses propres appareils.
- Des environnements de laboratoire.
- Des plateformes conçues pour l'entraînement.
- Des systèmes pour lesquels une autorisation explicite a été obtenue.

## 7. Exemple réel : les outils derrière la légende

### The Matrix Reloaded (2003)

Dans une scène célèbre de *The Matrix Reloaded*, Trinity utilise Nmap pour scanner une cible.

La scène fait également référence à une vulnérabilité SSH réelle et documentée, CVE-2001-0144.

Cet exemple illustre le fait que les outils de hacking utilisés dans les films peuvent être de véritables outils professionnels.

Nmap est un outil libre et open-source utilisé aussi bien par les administrateurs réseau que par les spécialistes en sécurité.

## 8. Contre-mesures défensives

### Scanner son propre réseau

Utiliser Nmap sur son propre réseau permet d'identifier les ports ouverts et les services oubliés.

### Surveiller son trafic

Wireshark permet d'observer les connexions et les paquets qui circulent sur un réseau.

### Détecter les scans

Un scan de ports peut générer une activité inhabituelle détectable par les outils de surveillance.

### Tester ses propres défenses

Les défenseurs utilisent les mêmes outils que les attaquants afin d'identifier les faiblesses de leurs systèmes.

## 9. Questions fréquentes

### Ai-je besoin d'un système d'exploitation spécialisé ?

Non. Un navigateur et un terminal suffisent pour commencer.

Les distributions Linux orientées sécurité regroupent de nombreux outils, mais elles ne sont pas indispensables au début.

### Quel outil apprendre en premier ?

Le navigateur et le terminal.

Ensuite, Nmap constitue un premier outil spécialisé naturel lorsque les bases du réseau sont comprises.

### Ces outils sont-ils légaux à télécharger ?

Oui. Nmap, Wireshark et les autres outils sont légaux à télécharger.

Le point essentiel est leur utilisation : il faut disposer d'une autorisation pour tester les systèmes concernés.

### Metasploit est-il de la triche ?

Non. Les professionnels utilisent des frameworks pour gagner en efficacité.

La compétence consiste à comprendre les exploits, à choisir les bons outils et à interpréter les résultats.

### Quelle compétence est la plus importante ?

Le terminal.

Presque tous les outils de cette boîte à outils peuvent être utilisés depuis celui-ci.

## 10. Fiche de référence rapide

| Outil | Fonction |
|---|---|
| Nmap | Identifier les ports et services ouverts |
| Wireshark | Lire le trafic réseau |
| Proxy d'interception | Capturer et modifier les requêtes web |
| Hashcat | Tester des mots de passe contre des hashes |
| John the Ripper | Casser des hashes de mots de passe |
| Metasploit | Lancer et gérer des exploits |
| Navigateur | Base du hacking web |
| Terminal | Base de nombreux outils |

## 11. Liste de départ

- [ ] Maîtriser le navigateur et le terminal.
- [ ] Comprendre les ports avant d'apprendre Nmap.
- [ ] Ajouter un outil lorsqu'on rencontre le problème qu'il résout.
- [ ] Comprendre les commandes avant de les exécuter.
- [ ] Utiliser uniquement des cibles autorisées.

## Conclusion

La maîtrise de la boîte à outils repose sur la compréhension et non sur la quantité d'outils possédés.

Les outils sont accessibles au public et utilisés par les professionnels de la sécurité.

La véritable compétence consiste à comprendre :
- Le problème à résoudre.
- L'outil adapté.
- Les résultats obtenus.
- Les limites de l'outil.
- Les conditions légales de son utilisation.

**Comprendre la tâche vaut mieux que posséder l'outil.**

**Un outil maîtrisé en profondeur vaut mieux que dix outils connus de nom.**

## Source

HackerDNA Course — Initiation au hacking  
Chapitre 9 : La boîte à outils du hacker
