# Catalogue des outils Kali Linux

> Catalogue de référence des outils Kali Linux, regroupés par fonction. La distribution et son catalogue évoluent : cette liste est à compléter et vérifier au fil des versions. Les options exactes dépendent de la version et sont à consulter via `outil --help` ou `man outil`.
>
> **Usage autorisé uniquement :** laboratoire personnel, CTF, systèmes dont l'audit est explicitement autorisé. Les paramètres pouvant déclencher une exploitation, un bruteforce, une interception ou une action intrusive ne sont pas détaillés ici.

Sources principales : [Kali Tools – liste officielle](https://www.kali.org/tools/all-tools/) · [Documentation Kali Tools](https://www.kali.org/docs/tools/kali-tools/)

## Réseau, inventaire et diagnostic

| Outil / commande | Description | Arguments / options (repères) | Ports associés |
|---|---|---|---|
| nmap | Inventaire réseau et découverte de services | `-h` aide; `-oN/-oX` sortie; `-p` sélection de ports (usage autorisé) | Ports ciblés selon le service |
| netcat (nc) | Connexions TCP/UDP et diagnostic de flux | `-h` aide; `-v` verbosité; `-w` délai; `-z` vérification de connexion | Port choisi |
| ss | Affiche sockets et connexions locales | `-t/-u` TCP/UDP; `-l` écoute; `-n` numérique; `-p` processus | Ports locaux |
| ip | Configuration et état interfaces/routage | `addr`, `link`, `route`, `-s` statistiques | N/A |
| ping | Vérifie la joignabilité IP/ICMP | `-c` nombre; `-W` délai; `-i` intervalle | Aucun (ICMP) |
| traceroute | Trace le chemin réseau | `-n` sans résolution DNS; `-m` TTL max; `-w` délai | UDP par défaut selon implémentation |
| mtr | Diagnostic continu de route et pertes | `-r` rapport; `-c` cycles; `-n` numérique | ICMP/UDP selon mode |
| dig | Requêtes DNS et inspection des réponses | `+short`, `+trace`, `+noall`, `+answer` | 53 TCP/UDP |
| host | Recherche DNS simple | `-t` type d'enregistrement; `-a` détails | 53 TCP/UDP |
| whois | Informations d'enregistrement de domaines/IP | `-h` serveur; nom/IP à rechercher | 43 TCP |
| curl | Client HTTP(S), transfert et test d'API | `-I` en-têtes; `-v` diagnostic; `-o` fichier; `-L` redirections | 80, 443 ou port du service |
| wget | Téléchargement HTTP/HTTPS/FTP | `-O` nom fichier; `-q` silencieux; `--spider` vérification | 80, 443, 21 selon URL |
| tcpdump | Capture et analyse de trafic réseau | `-i` interface; `-c` nombre; `-w` fichier; `-r` lecture capture | Tous ports capturés |
| Wireshark | Analyse graphique de captures réseau | filtres de capture/affichage; ouverture PCAP | Tous ports capturés |
| tshark | Analyse de capture en CLI | `-r` fichier; `-Y` filtre d'affichage; `-T` format | Tous ports capturés |
| tcpflow | Reconstruction de flux TCP depuis capture | `-r` PCAP; `-o` dossier de sortie | Ports présents dans capture |
| arp | Affiche/modifie cache ARP (outil legacy) | `-a` affichage; `-n` numérique | N/A (ARP) |
| arping | Diagnostic ARP sur réseau local | interface, cible, compte/intervalle selon version | N/A (ARP) |
| ethtool | Informations et réglages interface Ethernet | `-i` pilote; `-S` statistiques; `-k` offloads | N/A |
| nmcli | Gestion réseau via NetworkManager | `device`, `connection`, `radio`; `-t` format | N/A |
| iperf3 | Mesure de débit entre deux hôtes | `-c` client; `-s` serveur; `-p` port; `-t` durée | 5201 par défaut |
| socat | Relais de flux et conversions de sockets | `-d` diagnostic; `-v` flux verbose | Ports configurés |
| ncat | Variante Ncat de Nmap pour connexions et flux | `-h` aide; `-v` diagnostic; `-p` port | Port choisi |
| lsof | Liste fichiers ouverts et sockets par processus | `-i` sockets; `-P` ports numériques; `-n` sans DNS | Ports en écoute/connexion |
| fping | Vérification ICMP de plusieurs hôtes | `-a` joignables; `-u` injoignables; `-c` cycles | Aucun (ICMP) |
| netdiscover | Découverte d'hôtes sur LAN par ARP | interface, plage, mode passif selon version | N/A (ARP) |

## Web, HTTP et analyse applicative

| Outil / commande | Description | Arguments / options (repères) | Ports associés |
|---|---|---|---|
| Burp Suite | Proxy et suite d'analyse de sécurité web | paramètres projet/proxy; aide intégrée | 80, 443 et ports web |
| OWASP ZAP | Proxy d'analyse web et tests de sécurité | `-cmd` CLI; `-config`; `-dir` | 80, 443 |
| ffuf | Fuzzer web polyvalent (audit autorisé) | `-h` aide; paramètres de sortie/configuration décrits dans l'aide | 80, 443, port web |
| gobuster | Enumération de ressources web/DNS (audit autorisé) | `-h` aide; `-o` sortie; options de mode | 80, 443, DNS |
| feroxbuster | Exploration de contenu web | `-h` aide; `-o` fichier; réglages de sortie | 80, 443 |
| dirsearch | Recherche de chemins web | `-h` aide; `-o` sortie; options de format | 80, 443 |
| whatweb | Identification de technologies web | `-h` aide; `--log-brief` sortie | 80, 443 |
| wafw00f | Identification de pare-feu applicatifs WAF | `-h` aide; options de rapport | 80, 443 |
| nikto | Vérifications de configuration/risques web | `-h` aide; `-output` rapport; `-Format` format | 80, 443 |
| httpx | Vérification et métadonnées HTTP de domaines/hôtes | `-h` aide; `-json` sortie JSON; `-status-code` | 80, 443 et ports web |
| sqlmap | Outil d'audit SQLi automatisé; usage intrusif possible | options sensibles non listées; lire l'aide et n'utiliser que sur environnement autorisé | Port web de l'application |
| joomscan | Audit d'installations Joomla | `-h` aide; options de rapport | 80, 443 |
| WPScan | Audit de sécurité WordPress | `--help`; `--format` rapport; options de mise à jour | 80, 443 |
| SSLyze | Analyse de configuration TLS/SSL | `--help`; options de sortie JSON | 443 ou port TLS |
| testssl.sh | Vérification TLS et configuration SSL | `--help`; `--jsonfile` rapport | 443 ou port TLS |
| sslscan | Analyse des paramètres TLS | `--help`; options de sortie | 443 ou port TLS |
| GVM / Greenbone | Gestion de vulnérabilités et scans | `gvm-check-setup`, `gvm-start`, `gvm-stop` | 9392/9390 selon configuration |
| OpenVAS | Scanner de vulnérabilités (composant GVM) | options via aide et interface GVM | Ports cibles selon profil |
| Caido | Proxy web d'audit | configuration via interface/CLI | 80, 443, ports proxy |
| mitmproxy | Proxy HTTP(S) interactif et scripts | `-p` port; `-w` sauvegarde; `-r` lecture | Port proxy configuré |

## OSINT et reconnaissance publique

| Outil / commande | Description | Arguments / options (repères) | Ports associés |
|---|---|---|---|
| theHarvester | Recherche d'informations publiques sur domaines | `-h` aide; `-d` domaine; `-b` source (selon version) | 80/443, DNS |
| Maltego | Graphes de relations OSINT | transformations, sources et export depuis l'interface | Selon sources |
| recon-ng | Framework OSINT modulaire | commandes internes; `help`; modules et workspace | Selon sources |
| SpiderFoot | Automatisation OSINT et corrélation | `-h` aide; `-l` écoute locale; options UI/scan | Interface locale; sources externes |
| Sherlock | Recherche de présence de pseudonymes sur services publics | `-h` aide; sortie fichier selon version | 80/443 |
| maigret | Recherche de comptes par nom/pseudo | `-h` aide; options de rapport | 80/443 |
| dnsenum | Collecte et audit DNS | `-h` aide; `-o` rapport | 53 TCP/UDP |
| dnsrecon | Reconnaissance DNS | `-h` aide; `-d` domaine; `-j` JSON | 53 TCP/UDP |
| subfinder | Découverte passive de sous-domaines | `-h` aide; `-o` sortie; `-silent` | DNS, HTTPS sources |
| Amass | Cartographie d'assets et sous-domaines | `-h` aide; modes et fichiers de sortie | DNS/HTTPS |
| assetfinder | Recherche de domaines et sous-domaines publics | `-h` aide; domaine à rechercher | DNS/HTTPS |
| waybackurls | Extraction d'URLs depuis Wayback Machine | entrée domaine; redirection de sortie | HTTPS |
| gau | Collecte d'URLs archivées/publiques | `-h` aide; `-o` sortie | HTTPS |
| Photon | Collecte d'URLs, liens et ressources publiques | `-h` aide; options de sortie | 80, 443 |
| exiftool | Lecture/édition de métadonnées de fichiers | `-h` aide; `-G` groupes; `-json` sortie | N/A |
| metagoofil | Recherche de documents publics et métadonnées | `-h` aide; options rapport | HTTPS |
| searchsploit | Recherche locale dans Exploit-DB | `-h` aide; `-w` URL; `-m` copie (prudence) | N/A (base locale) |

## Wi-Fi, Bluetooth, radio et IoT

| Outil / commande | Description | Arguments / options (repères) | Ports associés |
|---|---|---|---|
| aircrack-ng suite | Suite d'analyse/audit Wi-Fi | aide de chaque composant; options d'analyse/capture non détaillées | 802.11; N/A TCP |
| iw | Configuration/inspection Wi-Fi Linux | `dev`, `info`, `list`, `reg` | N/A |
| wavemon | Moniteur Wi-Fi en terminal | options via `--help`; interface sélectionnée | N/A |
| Kismet | Détection et observation réseau sans fil | `-c` source; `-f` fichier config; `-h` aide | Interface web locale configurable |
| bluez / bluetoothctl | Gestion et diagnostic Bluetooth | commandes interactives `help`, `show`, `devices` | N/A (Bluetooth) |
| bettercap | Framework d'observation/audit réseau et protocoles | options générales et modules via aide; fonctions intrusives non détaillées | Ports selon module |
| hcxdumptool | Capture/audit Wi-Fi spécialisé | paramètres sensibles non détaillés; consulter aide et cadre autorisé | 802.11 |
| reaver | Audit WPS (peut être intrusif) | paramètres d'attaque non listés | 802.11/WPS |
| wifite | Automatisation d'audits Wi-Fi (intrusive possible) | options d'attaque non listées | 802.11 |
| rfkill | Activer/désactiver radios | `list`, `block`, `unblock` | N/A |
| rtl-sdr | Réception radio SDR | options propres à l'application SDR | Fréquences radio, pas ports TCP |
| GNU Radio | Traitement de signaux radio | flowgraphs et paramètres de blocs | N/A |

## Forensics, fichiers et récupération

| Outil / commande | Description | Arguments / options (repères) | Ports associés |
|---|---|---|---|
| Autopsy | Analyse forensique numérique GUI | cas, sources, modules via interface | N/A |
| Sleuth Kit | Analyse systèmes de fichiers et images disque | `-h` aide; options selon utilitaire | N/A |
| testdisk | Récupération partitions/données | menus et paramètres via aide | N/A |
| photorec | Récupération de fichiers | options de destination et type via aide | N/A |
| foremost | Carving de fichiers | `-i` image; `-o` sortie; `-t` types | N/A |
| scalpel | Carving configurable | `-c` config; `-o` sortie | N/A |
| binwalk | Analyse de signatures/firmware | `-h` aide; `-e` extraction (prudence); `-o` offset | N/A |
| bulk_extractor | Extraction d'artefacts d'images | `-o` sortie; options de scanners | N/A |
| volatility3 | Analyse mémoire et artefacts | `-h` aide; `-f` image mémoire; plugins | N/A |
| strings | Recherche de chaînes dans binaires | `-a` tous segments; `-n` longueur min | N/A |
| file | Identification type de fichier | `-b` sortie courte; `-i` MIME | N/A |
| xxd | Hexdump et conversion hexadécimale | `-l` longueur; `-s` offset; `-r` inverse | N/A |
| hashdeep | Hachage et comparaison de fichiers | `-c` hash; `-r` récursif; `-l` liste | N/A |
| sha256sum | Calcul/validation SHA-256 | `-c` vérification; fichiers en entrée | N/A |
| dd | Copie bas niveau de données | `if=` source; `of=` destination; `bs=` bloc (attention destructive) | N/A |
| Guymager | Imagerie forensique disque GUI | paramètres d'acquisition dans interface | N/A |
| chntpw | Inspection/modification de registres Windows hors ligne | options via aide; utiliser sur image autorisée | N/A |
| hivex | Outils de lecture d'hives Windows | commandes `hivex*`; fichier hive | N/A |

## Reverse engineering, développement et debugging

| Outil / commande | Description | Arguments / options (repères) | Ports associés |
|---|---|---|---|
| Ghidra | Désassemblage et décompilation | projet, scripts, import via GUI | N/A |
| radare2 | Framework reverse engineering | `-h` aide; `-A` analyse auto; `-q` silencieux | N/A |
| Cutter | GUI pour reverse engineering (radare2) | options de projet via interface | N/A |
| JADX | Décompilation Android | `-d` dossier; `-r` ressources | N/A |
| apktool | Décodage/reconstruction APK | `d` décoder; `b` construire; `-o` sortie | N/A |
| Frida | Instrumentation dynamique | `-h` aide; options de serveur/client | 27042/27043 souvent utilisés, configurables |
| GDB | Debugger | `-q` silencieux; `-p` PID; `-x` script | N/A |
| strace | Tracer appels système | `-p` PID; `-o` sortie; `-f` enfants | N/A |
| ltrace | Tracer appels de bibliothèques | `-p` PID; `-o` sortie | N/A |
| objdump | Analyse objets et désassemblage | `-d` désassemble; `-x` headers; `-s` sections | N/A |
| readelf | Lecture headers ELF | `-h` header; `-S` sections; `-l` segments | N/A |
| NASM | Assembleur | `-f` format; `-o` sortie | N/A |
| Python | Scripts et automatisation | `-h` aide; `-m` module; `-c` code | N/A |
| Git | Gestion de versions | `status`, `log`, `diff`, `-C` dépôt | N/A |
| Docker | Conteneurs | `ps`, `images`, `run`, `-p` ports | Ports exposés/configurés |

## Audit de mots de passe et authentification

> Les outils de cette catégorie peuvent servir à auditer des secrets, mais également à compromettre des comptes. Les arguments permettant le bruteforce, le cracking ou le contournement d'authentification ne sont pas détaillés.

| Outil / commande | Description | Arguments / options (repères) | Ports associés |
|---|---|---|---|
| John the Ripper | Audit de robustesse de mots de passe et hashes | aide, formats et rapports; paramètres de cracking non détaillés | N/A (offline) |
| Hashcat | Audit de hashes utilisant CPU/GPU | `--help`; paramètres de benchmark/affichage; modes d'attaque non détaillés | N/A (offline) |
| Hydra | Test d'authentification multi-protocoles | options d'audit intrusif non détaillées | Services testés |
| Medusa | Audit d'authentification réseau | paramètres d'attaque non détaillés | Services testés |
| CeWL | Génération de listes à partir de contenu web | `-h` aide; `-w` sortie; options de collecte | 80, 443 |
| crunch | Génération de chaînes/listes | paramètres de génération non détaillés | N/A |
| hashid | Identification probable d'un type de hash | `-h` aide; `-m` modes; `-j` JSON | N/A |
| name-that-hash | Identification de hashes | `-h` aide; options de sortie | N/A |
| pw-inspector | Analyse de règles de complexité | `-h` aide; options de critères | N/A |

## Exploitation, post-exploitation et frameworks

> Références de familles d'outils uniquement. Les commandes, options et chaînes opérationnelles de prise de contrôle, de persistance, de pivot ou d'exfiltration ne sont pas reproduites.

| Outil / commande | Description | Arguments / options (repères) | Ports associés |
|---|---|---|---|
| Metasploit Framework (msfconsole) | Framework modulaire de test de sécurité | `-h` aide; `-q` silencieux; options de configuration | Selon module |
| msfvenom | Générateur de payloads (risque élevé) | options de génération non détaillées | Selon payload |
| Exploit-DB / searchsploit | Base de références d'exploits et recherche locale | `-h` aide; options d'affichage/recherche | N/A |
| Empire | Framework post-exploitation | détails d'usage offensif non détaillés | Selon configuration |
| BloodHound | Cartographie des relations Active Directory | ingestion et interface; options via aide | 7687/7474 selon édition/config |
| SharpHound | Collecteur de données AD pour BloodHound | paramètres de collecte sensibles non détaillés | AD, selon environnement |
| NetExec | Audit de services et environnements réseau | arguments opérationnels intrusifs non détaillés | SMB 445, SSH 22, WinRM 5985/5986 selon module |
| Responder | Outil d'analyse/audit de résolution de noms et protocoles locaux | options d'empoisonnement non détaillées | 137/138 UDP, 139/445 TCP, autres selon config |
| Impacket | Collection de scripts/protocoles réseau | liste des scripts et aides individuelles; actions offensives non détaillées | SMB 445, Kerberos 88, LDAP 389/636 selon script |
| mitm6 | Audit IPv6/AD (risque d'interception) | paramètres d'interception non détaillés | DHCPv6 547 UDP, DNS 53, services AD |
| Ligolo-ng | Tunnel/pivot réseau | options de pivot non détaillées | ports configurés |
| Chisel | Tunnel TCP/UDP via HTTP | `--help`; port serveur configuré | Port configuré |
| Proxychains | Routage d'applications via proxy | `-f` fichier config; options de lancement | Ports proxy configurés |
| SSH | Connexion et administration distante sécurisée | `-p` port; `-i` clé; `-L/-R` tunnels (à utiliser avec autorisation) | 22 par défaut |
| OpenVPN | VPN | `--config` fichier; `--remote` serveur (config) | 1194 fréquent, configurable |
| WireGuard | VPN moderne | `wg`, `wg-quick`; configuration | Port configuré |

## VoIP, bases de données et services spécialisés

| Outil / commande | Description | Arguments / options (repères) | Ports associés |
|---|---|---|---|
| SIPVicious | Suite d'audit SIP | aide; modes intrusifs non détaillés | 5060 UDP/TCP, 5061 TLS |
| sipp | Générateur/testeur de trafic SIP | `-h` aide; paramètres de scénario | 5060/5061 selon test |
| sipsak | Diagnostic SIP | `-h` aide; options de requête | 5060/5061 |
| sqlninja | Outil d'audit SQL Server/web (risque élevé) | options d'exploitation non détaillées | 1433 et port web |
| oscanner | Audit Oracle | options via aide | 1521 TCP |
| redis-tools | Client et outils Redis | `redis-cli -h` hôte; `-p` port; `INFO` (selon droits) | 6379 par défaut |
| mysql | Client MySQL/MariaDB | `-h` hôte; `-P` port; `-u` utilisateur | 3306 |
| psql | Client PostgreSQL | `-h` hôte; `-p` port; `-U` utilisateur | 5432 |
| smbclient | Client SMB | `-L` liste (autorisée); `-I` IP; `-p` port | 445, 139 |
| rpcclient | Client RPC SMB | aide; paramètres d'accès autorisé non détaillés | 445, 139 |
| ldapsearch | Recherche LDAP | `-H` URI; `-b` base DN; `-x` auth simple | 389, 636 |
| snmpwalk | Exploration SNMP autorisée | `-v` version; `-c` communauté (secret); `-On` OID | 161 UDP |
| ike-scan | Diagnostic/audit IKE/IPsec | détails d'audit intrusif non détaillés | 500 UDP, 4500 UDP |
| enum4linux-ng | Audit d'informations SMB/Windows | `-h` aide; `-oJ` JSON | 445, 139 |
| rpcinfo | Inventaire RPC d'un serveur autorisé | `-p` liste services | 111 TCP/UDP |
| nfs-utils | Client/diagnostic NFS | `showmount`; options mount | 2049 TCP/UDP; 111 RPC |
| snmp | Outils SNMP | `-h` aide; options de version/format | 161 UDP, 162 UDP traps |

## Utilitaires, éditeurs et outils de support

| Outil / commande | Description | Arguments / options (repères) | Ports associés |
|---|---|---|---|
| 7z | Compression/archivage | `a` ajouter; `x` extraire; `-o` dossier | N/A |
| unzip | Extraction ZIP | `-l` liste; `-d` destination | N/A |
| tar | Archives tar | `-c` créer; `-x` extraire; `-f` fichier | N/A |
| openssl | Cryptographie, certificats et TLS | `version`, `s_client`, `x509`; options selon commande | Port TLS si connexion |
| gpg | Gestion OpenPGP | `--list-keys`; `--verify`; `--output` | N/A |
| vim / nano | Éditeurs de texte | options d'ouverture; commandes internes | N/A |
| tmux | Multiplexeur terminal | `-L` socket; `-f` config | N/A |
| screen | Multiplexeur terminal | `-S` session; `-ls` liste | N/A |
| jq | Manipulation JSON | `-r` texte; `-c` compact; filtre | N/A |
| yq | Manipulation YAML/JSON/XML selon version | aide; filtre et format | N/A |
| grep | Recherche textuelle | `-i` insensible casse; `-r` récursif; `-n` lignes | N/A |
| awk | Traitement de texte structuré | `-F` séparateur; script awk | N/A |
| sed | Transformation de texte | `-n`; expressions; `-i` modifie fichier (prudence) | N/A |
| find | Recherche de fichiers | `-name`; `-type`; `-mtime` | N/A |
| rsync | Synchronisation de fichiers | `-a` archive; `-v` verbose; `-n` simulation | 873/SSH 22 selon mode |
| apt | Gestion paquets Debian/Kali | `update`; `install`; `remove`; `search` | 80/443 dépôts |
| dpkg | Gestion packages Debian | `-l` liste; `-i` installation locale | N/A |
| systemctl | Gestion services systemd | `status`; `start`; `stop`; `enable` | Dépend du service |
| journalctl | Consultation journaux systemd | `-u` service; `-f` suivi; `--since` date | N/A |

## Références de catégories Kali

Le catalogue officiel comprend notamment les familles : information-gathering, vulnerability, web, exploitation, post-exploitation, passwords, forensics, reverse-engineering, sniffing/spoofing, wireless, Bluetooth, SDR, RFID, hardware, VoIP, crypto/stego, fuzzing, reporting, protection, recovery et responding. Le nombre et les noms des paquets changent au fil des versions.

Pour compléter ce catalogue tool-by-tool, utiliser les fiches officielles de chaque paquet sur [Kali Tools](https://www.kali.org/tools/all-tools/). Pour une option précise, vérifier la version installée avec `outil --help` et `man outil`.

---

## Ressource complémentaire

🎓 [HackerDNA — plateforme d'apprentissage en cybersécurité](https://hackerdna.com/?ref=guanlin)
