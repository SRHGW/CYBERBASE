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

    161ebd7d45089b3446ee4e0d86dbcf92:P@ssw0rd
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

## 12. Cheat Sheet — Outils de cybersécurité

| Outil | Utilisation | Commande | Options / Arguments |
|---|---|---|---|
| Nmap | Scan de ports | `nmap <IP>` | `-F`, `-sC`, `-sV`, `-p`, `-p-`, `-O`, `-A`, `-Pn`, `-oN`, `-oX`, `-oA` |
| Masscan | Scan rapide de ports | `masscan <IP> -p<PORTS>` | `-p`, `--rate`, `-oL`, `-oJ` |
| RustScan | Scan rapide de ports | `rustscan -a <IP>` | `-p`, `-b`, `--ulimit` |
| Netcat | Connexions TCP/UDP | `nc <IP> <PORT>` | `-l`, `-v`, `-n`, `-u`, `-z` |
| Socat | Relais réseau | `socat <TYPE1> <TYPE2>` | `TCP:`, `UDP:`, `LISTEN:`, `EXEC:` |
| arp-scan | Découverte réseau local | `arp-scan --localnet` | `--interface`, `--localnet` |
| fping | Ping multiple | `fping <IP>` | `-a`, `-g`, `-c`, `-r` |
| tcpdump | Capture réseau | `tcpdump` | `-i`, `-n`, `-w`, `-r`, `-c`, `-A`, `-X` |
| TShark | Analyse réseau CLI | `tshark` | `-i`, `-r`, `-Y`, `-f`, `-w` |
| Wireshark | Analyse réseau GUI | `wireshark` | Filtres : `ip.addr`, `tcp.port`, `http`, `dns` |
| Zeek | Analyse réseau | `zeek -r <PCAP>` | `-r`, `-C`, `LogAscii` |
| Suricata | IDS/IPS | `suricata -r <PCAP>` | `-r`, `-i`, `-c`, `-T` |
| Snort | Détection intrusion | `snort` | `-c`, `-i`, `-r`, `-A` |
| dig | Requêtes DNS | `dig <DOMAIN>` | `A`, `AAAA`, `MX`, `NS`, `TXT`, `ANY`, `+short` |
| nslookup | Résolution DNS | `nslookup <DOMAIN>` | `<DOMAIN>`, `<DNS>` |
| host | Recherche DNS | `host <DOMAIN>` | `-t A`, `-t MX`, `-t NS` |
| Amass | Reconnaissance domaines | `amass enum -d <DOMAIN>` | `-d`, `-passive`, `-active`, `-o` |
| Subfinder | Sous-domaines | `subfinder -d <DOMAIN>` | `-d`, `-silent`, `-o`, `-all` |
| DNSRecon | Reconnaissance DNS | `dnsrecon -d <DOMAIN>` | `-d`, `-t`, `-D`, `-n` |
| theHarvester | OSINT domaines | `theHarvester -d <DOMAIN>` | `-d`, `-b`, `-l`, `-f` |
| Shodan | Recherche appareils Internet | `shodan search <QUERY>` | `search`, `host`, `download`, `count` |
| Censys | Recherche infrastructure | Recherche Web | `services.port`, `services.service_name` |
| Maltego | Relations OSINT | Interface graphique | Transforms, Entities |
| SpiderFoot | OSINT automatisé | `sf.py` | Modules, Scan |
| ExifTool | Métadonnées | `exiftool <FILE>` | `-all`, `-json`, `-csv`, `-r` |
| Burp Suite | Proxy HTTP | Interface graphique | Proxy, Repeater, Intruder, Scanner |
| OWASP ZAP | Audit web | `zap.sh` | `-cmd`, `-quickurl`, `-quickout` |
| Caido | Proxy HTTP | Interface graphique | Intercept, Replay, Automate |
| mitmproxy | Proxy HTTP CLI | `mitmproxy` | `-p`, `-w`, `-r`, `-s` |
| curl | Requêtes HTTP | `curl <URL>` | `-I`, `-X`, `-H`, `-d`, `-o`, `-v`, `-k` |
| wget | Téléchargement | `wget <URL>` | `-O`, `-q`, `-r`, `-c` |
| Gobuster | Énumération web | `gobuster dir` | `-u`, `-w`, `-x`, `-t`, `-o` |
| Feroxbuster | Énumération web | `feroxbuster -u <URL>` | `-u`, `-w`, `-x`, `-t`, `-o` |
| ffuf | Fuzzing web | `ffuf -u <URL>/FUZZ` | `-w`, `-u`, `-mc`, `-fc`, `-fs`, `-recursion` |
| Dirsearch | Énumération web | `dirsearch -u <URL>` | `-u`, `-w`, `-e`, `-x`, `-o` |
| Nikto | Audit web | `nikto -h <URL>` | `-h`, `-p`, `-ssl`, `-output` |
| WhatWeb | Fingerprinting web | `whatweb <URL>` | `-a`, `-v`, `--color` |
| Nuclei | Scan vulnérabilités | `nuclei -u <URL>` | `-u`, `-t`, `-severity`, `-o`, `-rl` |
| SQLmap | Tests SQLi | `sqlmap -u <URL>` | `-u`, `--data`, `--cookie`, `--dbs`, `--batch` |
| WPScan | Audit WordPress | `wpscan --url <URL>` | `--url`, `--enumerate`, `--plugins-detection` |
| testssl.sh | Audit TLS | `testssl.sh <DOMAIN>` | `--fast`, `--full`, `--jsonfile` |
| SSLyze | Audit SSL/TLS | `sslyze <DOMAIN>` | `--regular`, `--json_out` |
| Searchsploit | Recherche exploits | `searchsploit <QUERY>` | `-w`, `-m`, `-x`, `--update` |
| Metasploit | Framework exploitation | `msfconsole` | `search`, `use`, `show options`, `set`, `run` |
| BeEF | Sécurité navigateur | `beef` | Interface Web |
| Impacket | Protocoles Windows | `impacket-<SCRIPT>` | Options propres à chaque script |
| BloodHound | Active Directory | Interface graphique | Collectors, Graphes |
| PingCastle | Audit AD | `PingCastle.exe` | `--healthcheck`, `--scanner` |
| Hashcat | Audit hashes | `hashcat -m <MODE>` | `-m`, `-a`, `-w`, `-o`, `--show`, `--status` |
| John the Ripper | Audit hashes | `john <FILE>` | `--wordlist`, `--format`, `--show`, `--rules` |
| Hydra | Audit authentification | `hydra` | `-l`, `-L`, `-p`, `-P`, `-t`, `-V` |
| Medusa | Audit authentification | `medusa` | `-h`, `-u`, `-U`, `-p`, `-P`, `-M` |
| CeWL | Génération wordlist | `cewl <URL>` | `-w`, `-m`, `-d`, `-c` |
| Crunch | Génération wordlist | `crunch <MIN> <MAX>` | `-o`, `-t`, `-f` |
| OpenSSL | Cryptographie | `openssl` | `enc`, `dgst`, `s_client`, `x509`, `genpkey` |
| GnuPG | Chiffrement | `gpg` | `-c`, `-d`, `-e`, `-s`, `--verify` |
| CyberChef | Encodage / décodage | Interface Web | Base64, Hex, URL, XOR, Hash |
| age | Chiffrement fichiers | `age -r <KEY>` | `-r`, `-R`, `-o`, `-d` |
| Ghidra | Reverse engineering | Interface graphique | Disassembly, Decompiler |
| IDA Free | Reverse engineering | Interface graphique | Disassembly, Graph |
| radare2 | Analyse binaire | `r2 <FILE>` | `-A`, `-q`, `-c` |
| Cutter | Reverse engineering GUI | Interface graphique | Analyse, Graphes |
| x64dbg | Debug Windows | Interface graphique | Breakpoints, Registers |
| WinDbg | Debug Windows | `windbg` | `!analyze`, `k`, `lm` |
| Frida | Instrumentation | `frida` | `-U`, `-f`, `-n`, `-l` |
| YARA | Détection fichiers | `yara <RULE> <FILE>` | `-r`, `-s`, `-m`, `-w` |
| Capa | Analyse capacités | `capa <FILE>` | `-v`, `-j`, `-r` |
| Strings | Extraction chaînes | `strings <FILE>` | `-a`, `-n`, `-el`, `-eb` |
| Autopsy | Forensic | Interface graphique | Cases, Images, Timeline |
| Volatility 3 | Analyse RAM | `vol -f <DUMP>` | `windows.info`, `pslist`, `netscan` |
| FTK Imager | Acquisition disque | Interface graphique | Image, Export, Verify |
| Plaso | Timeline forensic | `log2timeline.py` | `-o`, `--storage-file` |
| KAPE | Collecte forensic | `kape.exe` | `--tsource`, `--tdest`, `--target` |
| ALEAPP | Forensic Android | `aleapp.py` | `-i`, `-o` |
| iLEAPP | Forensic iOS | `ileapp.py` | `-i`, `-o` |
| Sysinternals | Analyse Windows | Suite d'outils | Procmon, Autoruns, PsExec |
| Process Monitor | Analyse processus | `Procmon.exe` | Filtres, Capture |
| Process Explorer | Analyse processus | `procexp.exe` | Processus, DLL, Handles |
| Autoruns | Démarrage Windows | `autoruns.exe` | Logon, Services, Drivers |
| osquery | Requêtes système | `osqueryi` | SQL, Tables système |
| Lynis | Audit Linux | `lynis audit system` | `--quick`, `--tests`, `--logfile` |
| OpenSCAP | Conformité système | `oscap` | `info`, `eval`, `xccdf` |
| Wazuh | SIEM / EDR | Interface Web | Agents, Rules, Alerts |
| Graylog | Gestion logs | Interface Web | Search, Streams, Alerts |
| Splunk | SIEM | `splunk` | `search`, `index`, SPL |
| Nessus | Scan vulnérabilités | Interface Web | Policies, Scans |
| OpenVAS | Scan vulnérabilités | Interface Web | Targets, Tasks, Reports |
| Trivy | Scan vulnérabilités | `trivy image <IMAGE>` | `image`, `fs`, `config`, `repo` |
| Grype | Scan vulnérabilités | `grype <IMAGE>` | `dir:`, `sbom:` |
| Syft | Inventaire SBOM | `syft <IMAGE>` | `-o`, `cyclonedx`, `spdx` |
| Semgrep | Analyse code | `semgrep scan` | `--config`, `--json`, `--exclude` |
| Bandit | Audit Python | `bandit -r <DIR>` | `-r`, `-f`, `-o`, `-ll` |
| Checkov | Audit IaC | `checkov -d <DIR>` | `-d`, `-f`, `--framework`, `--output` |
| Gitleaks | Détection secrets | `gitleaks detect` | `detect`, `protect`, `--source`, `--report-format` |
| MobSF | Audit mobile | Interface Web | Static Analysis, Dynamic Analysis |
| JADX | Décompilation Android | `jadx <APK>` | `-d`, `-r`, `--show-bad-code` |
| Apktool | Analyse APK | `apktool d <APK>` | `d`, `b`, `-o`, `-f` |
| ADB | Android Debug Bridge | `adb devices` | `shell`, `pull`, `push`, `install`, `logcat` |
| Objection | Audit mobile | `objection` | `-g`, `explore`, `android` |
| Git | Gestion versions | `git` | `clone`, `status`, `add`, `commit`, `push`, `pull` |
| Docker | Conteneurs | `docker` | `run`, `exec`, `ps`, `images`, `build` |
| Kubernetes | Orchestration | `kubectl` | `get`, `describe`, `logs`, `exec`, `apply` |
| Terraform | Infrastructure as Code | `terraform` | `init`, `plan`, `apply`, `destroy` |
| Ansible | Automatisation | `ansible` | `-i`, `-m`, `-a`, `ansible-playbook` |
| GitHub / GitLab | Recherche de code et dépôts | Interface Web | Code, Issues, Commits, Releases |
| GitHub CLI | Gestion GitHub en terminal | `gh repo list` | `repo`, `issue`, `pr`, `auth` |
| Google Dorking | Recherche avancée OSINT | Requête Google | `site:`, `filetype:`, `intitle:`, `inurl:` |
| Wayback Machine | Historique de sites web | Interface Web | URL, dates, snapshots |
| urlscan.io | Analyse d'URL | Interface Web | URL, domaines, IP, requêtes |
| VirusTotal | Analyse fichiers et URL | Interface Web / API | `file`, `url`, `domain`, `ip` |
| Pwned Passwords | Vérification de compromission | Interface Web / API | Hash SHA-1, vérification de mot de passe |
| Recon-ng | Reconnaissance OSINT | `recon-ng` | Modules, Workspaces, Marketplace |
| Wappalyzer | Identification technologies web | Extension / Interface Web | CMS, Frameworks, Serveurs |
| Aquatone | Visualisation domaines web | `aquatone` | `scan`, `gather`, `report` |
| httpx | Vérification services HTTP | `httpx -l <FILE>` | `-title`, `-status-code`, `-tech-detect`, `-o` |
| Katana | Crawling web | `katana -u <URL>` | `-d`, `-jc`, `-kf`, `-o` |
| Arjun | Découverte paramètres HTTP | `arjun -u <URL>` | `-m`, `-o`, `-t` |
| ParamSpider | Recherche paramètres URL | `paramspider -d <DOMAIN>` | `-d`, `-o`, `--exclude` |
| WPScan | Audit WordPress | `wpscan --url <URL>` | `--api-token`, `--enumerate` |
| Chisel | Tunnel réseau | `chisel server` | `server`, `client`, `--reverse` |
| Ligolo-ng | Tunneling / pivot réseau | `ligolo-ng` | Agent, Proxy, Tunnels |
| Proxychains | Routage via proxy | `proxychains <COMMAND>` | `-q`, `-f` |
| GetNPUsers | Audit Kerberos AD | `GetNPUsers.py <DOMAIN>/` | `-dc-ip`, `-usersfile`, `-request` |
| GetUserSPNs | Audit SPN Kerberos AD | `GetUserSPNs.py <DOMAIN>/` | `-dc-ip`, `-request`, `-outputfile` |
| SMBClient (Impacket) | Interaction SMB | `smbclient.py <TARGET>` | `-target-ip`, `-hashes`, `-no-pass` |
| Evil-WinRM | Administration WinRM | `evil-winrm -i <IP>` | `-u`, `-p`, `-H`, `-s` |
| Rubeus | Audit Kerberos Windows | `Rubeus.exe` | `kerberoast`, `asreproast`, `triage` |
| Mimikatz | Analyse identifiants Windows | `mimikatz.exe` | Modules, commandes internes |
| LaZagne | Audit récupération identifiants | `laZagne.exe` | Modules, `all`, `browsers` |
| Chainsaw | Analyse journaux Windows | `chainsaw hunt <DIR>` | `hunt`, `search`, `dump`, `--sigma` |
| Sigma | Règles de détection | Fichiers YAML | Logsource, Detection, Condition |
| Velociraptor | DFIR / collecte endpoint | Interface Web / CLI | Hunts, Artifacts, Collect |
| Timesketch | Analyse chronologique forensic | Interface Web | Timelines, Events, Tags |
| Binwalk | Analyse firmware | `binwalk <FILE>` | `-e`, `-M`, `-E` |
| Checksec | Vérification protections binaires | `checksec --file=<FILE>` | PIE, NX, RELRO, Canary |
| GDB | Debugging binaire | `gdb <FILE>` | `run`, `break`, `info`, `x`, `disassemble` |
| Pwntools | Exploitation binaire / CTF | `python3` | `pwn`, `ELF`, `ROP`, `cyclic` |
| ROPgadget | Recherche gadgets ROP | `ROPgadget --binary <FILE>` | `--binary`, `--ropchain` |
| Pwndbg | Extension GDB exploitation | `gdb <FILE>` | `context`, `vmmap`, `telescope` |
| Docker Scout | Analyse sécurité images | `docker scout` | `quickview`, `cves`, `recommendations` |
| Falco | Détection comportement runtime | `falco` | Rules, Events, JSON |
| Kube-bench | Audit configuration Kubernetes | `kube-bench` | `run`, `--targets`, `--benchmark` |
| Kube-hunter | Audit sécurité Kubernetes | `kube-hunter` | Remote, Interface, Pod |
| Prowler | Audit cloud | `prowler` | AWS, Azure, GCP, `-M`, `-o` |
| ScoutSuite | Audit cloud | `scout` | AWS, Azure, GCP, Reports |
| Cloudsplaining | Analyse IAM AWS | `cloudsplaining` | `scan`, `download`, `--input-file` |
| TruffleHog | Détection secrets | `trufflehog git <URL>` | `git`, `filesystem`, `github`, `--json` |
| detect-secrets | Détection secrets dépôt | `detect-secrets scan` | `scan`, `audit`, `baseline` |
| Semgrep | Analyse statique de code | `semgrep scan` | Rules, Findings |
| OWASP Dependency-Check | Audit dépendances | `dependency-check.sh` | `--scan`, `--format`, `--out` |
| Snyk | Audit dépendances / code | `snyk test` | `test`, `code`, `container`, `monitor` |
| LanguageTool | Correction documentation | Interface Web | Orthographe, grammaire |


### Légende

- `<IP>` : adresse IP de la cible.
- `<DOMAIN>` : nom de domaine.
- `<URL>` : adresse URL.
- `<PORT>` : numéro de port.
- `<PORTS>` : liste ou plage de ports.
- `<FILE>` : fichier.
- `<DIR>` : répertoire.
- `<QUERY>` : requête de recherche.
- `<WORDLIST>` : liste de mots.

**Attention :** les options peuvent varier selon les versions et systèmes. Consulter la documentation officielle avant utilisation.

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
