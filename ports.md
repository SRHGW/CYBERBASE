# Catalogue des ports réseau

> Ports TCP/UDP classés par numéro croissant. Le numéro de port ne garantit pas le service : un service peut être configuré sur un autre port et un port peut être réutilisé. Cette première version liste les ports connus, courants et importants, pas la totalité des enregistrements IANA ni les 65 536 numéros.
>
> Plages : **0–1023** ports système/well-known; **1024–49151** ports enregistrés; **49152–65535** ports dynamiques/éphémères (plage courante, variable selon OS).

| Port | Protocole | Nom / service | Utilité |
|---:|---|---|---|
| 0 | TCP/UDP | Réservé | Port réservé; parfois utilisé comme port source spécial. |
| 1 | TCP | TCPMUX | Multiplexeur TCP historique, rarement utilisé. |
| 2 | TCP | Réservé | Réservé/obsolète. |
| 3 | TCP | Compression | Service de compression historique. |
| 5 | TCP | RJE | Remote Job Entry historique. |
| 7 | TCP/UDP | Echo | Renvoie les données reçues; service de diagnostic legacy. |
| 9 | TCP/UDP | Discard | Ignore les données; service de test legacy. |
| 11 | TCP | Systat | Service d'information système historique. |
| 13 | TCP/UDP | Daytime | Date et heure en texte. |
| 17 | TCP/UDP | Quote of the Day | Citation quotidienne, service historique. |
| 18 | TCP/UDP | Message Send Protocol | Protocole historique. |
| 19 | TCP/UDP | Chargen | Générateur de caractères, service legacy. |
| 20 | TCP | FTP-data | Canal de données FTP en mode actif. |
| 21 | TCP | FTP-control | Contrôle FTP (authentification/commandes). |
| 22 | TCP | SSH | Administration distante sécurisée, SFTP/SCP via SSH. |
| 23 | TCP | Telnet | Terminal distant non chiffré (à éviter sur réseau non sûr). |
| 25 | TCP | SMTP | Relais/envoi de courrier électronique. |
| 26 | TCP | SMTP alternate | Port alternatif rencontré dans certaines configurations. |
| 37 | TCP/UDP | Time | Service horaire historique. |
| 39 | UDP | RLP | Resource Location Protocol legacy. |
| 42 | TCP/UDP | WINS/Host Name Server | Service historique de résolution de noms. |
| 43 | TCP | WHOIS | Consultation d'informations d'enregistrement. |
| 49 | TCP | TACACS | Authentification/contrôle d'accès legacy. |
| 53 | TCP/UDP | DNS | Résolution de noms; TCP également pour transferts et réponses volumineuses. |
| 67 | UDP | DHCP-server | Serveur DHCP IPv4. |
| 68 | UDP | DHCP-client | Client DHCP IPv4. |
| 69 | UDP | TFTP | Transfert de fichiers simple, sans authentification. |
| 70 | TCP | Gopher | Protocole de documents historique. |
| 79 | TCP | Finger | Informations utilisateurs, service legacy. |
| 80 | TCP | HTTP | Web non chiffré. |
| 81 | TCP | HTTP-alt | Port alternatif web fréquemment configuré. |
| 82 | TCP | HTTP-alt | Port alternatif utilisé par certaines interfaces. |
| 88 | TCP/UDP | Kerberos | Authentification Kerberos (AD notamment). |
|  sun 89 | TCP | SU/MIT? | Port historique/réservé selon registre; vérifier l'assignation officielle. |
| 90 | TCP | DNSIX | Service militaire/historique. |
| 99 | TCP | Metagram Relay | Service historique. |
| 101 | TCP | NIC Host Name | Résolution de noms historique. |
| 102 | TCP | ISO-TSAP | Transport ISO/TSAP; automatisation/industrie dans certains environnements. |
| 104 | TCP | DICOM | Imagerie médicale (DICOM). |
| 105 | TCP | CCSO Nameserver | Annuaire historique. |
| 107 | TCP | Remote Telnet Service | Service legacy. |
| 109 | TCP | POP2 | Ancienne réception de mail. |
| 110 | TCP | POP3 | Réception de mail (non chiffrée). |
| 111 | TCP/UDP | rpcbind/portmapper | Découverte des services RPC. |
| 113 | TCP | Ident / Authentication | Identification de l'utilisateur d'une connexion (legacy). |
| 119 | TCP | NNTP | Usenet/news. |
| 123 | UDP | NTP | Synchronisation horaire. |
| 135 | TCP | MS RPC Endpoint Mapper | Découverte des endpoints RPC Windows. |
| 137 | UDP | NetBIOS Name Service | Résolution de noms NetBIOS. |
| 138 | UDP | NetBIOS Datagram | Datagrammes NetBIOS. |
| 139 | TCP | NetBIOS Session | Sessions SMB via NetBIOS. |
| 143 | TCP | IMAP | Accès aux courriels. |
| 144 | TCP | NewS | Service news historique. |
| 161 | UDP | SNMP | Gestion et supervision réseau. |
| 162 | UDP | SNMP Trap | Réception de notifications SNMP. |
| 163 | TCP/UDP | CMIP | Gestion réseau OSI historique. |
| 179 | TCP | BGP | Routage inter-domaines (Border Gateway Protocol). |
| 194 | TCP | IRC | Chat Internet Relay Chat. |
| 199 | TCP | SNMP multiplex | Service legacy. |
| 201 | TCP | AppleTalk | Service historique. |
| 209 | TCP | QMTP | Quick Mail Transfer Protocol. |
| 213 | TCP/UDP | IPX | Service historique. |
| 220 | TCP | IMAP3 | Ancienne variante IMAP. |
|  389 | TCP/UDP | LDAP | Annuaire LDAP. |
|  427 | TCP/UDP | SLP | Service Location Protocol. |
|  443 | TCP | HTTPS | HTTP chiffré TLS. |
|  443 | UDP | QUIC/HTTP3 | HTTP/3 sur QUIC (UDP). |
|  445 | TCP | SMB | Partage fichiers/imprimantes Windows, SMB direct. |
|  464 | TCP/UDP | Kerberos password change | Changement de mot de passe Kerberos. |
|  465 | TCP | SMTPS | SMTP sur TLS implicite (usage courant). |
|  500 | UDP | IKE | Négociation IPsec. |
|  502 | TCP | Modbus | Protocole industriel Modbus TCP. |
|  503 | TCP | Intradomaine | Service historique/réservé; usage variable. |
|  514 | UDP | Syslog | Envoi de journaux (non chiffré traditionnel). |
|  515 | TCP | LPD/LPR | Impression réseau legacy. |
|  520 | UDP | RIP | Protocole de routage RIP. |
|  521 | UDP | RIPng | RIP pour IPv6. |
|  524 | TCP | NCP | NetWare Core Protocol. |
|  530 | TCP | RPC | Service RPC historique. |
|  543 | TCP | Klogin | Connexion distante Kerberos legacy. |
|  544 | TCP | Kshell | Shell distant Kerberos legacy. |
|  548 | TCP | AFP | Apple Filing Protocol. |
|  554 | TCP/UDP | RTSP | Contrôle de flux média. |
|  560 | UDP | RMON | Remote Monitoring legacy. |
|  563 | TCP | NNTPS | NNTP sur TLS. |
|  587 | TCP | SMTP Submission | Soumission de mail par clients, souvent STARTTLS. |
|  593 | TCP | RPC over HTTP | RPC sur HTTP (Windows). |
|  600 | TCP | IPC | Service IPC historique. |
|  623 | UDP | IPMI | Gestion hors bande des serveurs (BMC). |
|  631 | TCP/UDP | IPP | Impression Internet Protocol. |
|  636 | TCP | LDAPS | LDAP sur TLS. |
|  639 | TCP | MSRP | Multi-protocol Routing. |
|  646 | TCP | LDP | Label Distribution Protocol (MPLS). |
|  647 | TCP | DHCPv6 failover | Failover DHCP legacy. |
|  648 | TCP | RRP | Registry Remote Protocol. |
|  651 | TCP | Syslog TLS | Journaux via TLS (RFC 5425). |
|  653 | TCP/UDP | RRP | Service de routage historique. |
|  654 | TCP | AODV | Ad hoc On-Demand Distance Vector. |
|  657 | TCP | IBM RMC | Resource Monitoring and Control. |
|  660 | TCP | Apple Music / legacy | Port assigné historiquement à services Apple. |
|  666 | TCP | Doom | Port souvent associé à Doom; usage de jeu historique. |
|  674 | TCP | ACAP | Application Configuration Access Protocol. |
|  691 | TCP | Exchange Routing | Routage Exchange historique. |
|  692 | TCP | Hyperwave | Hyperwave server. |
|  700 | TCP | EPP | Extensible Provisioning Protocol. |
|  701 | TCP | LMP | Link Management Protocol. |
|  702 | TCP | IRIS | Service historique. |
|  706 | TCP | SILC | Secure Internet Live Conferencing. |
|  711 | TCP | TDP | Service historique. |
|  720 | TCP | NETVIEW | Service historique. |
|  749 | TCP/UDP | Kerberos Admin | Administration Kerberos. |
|  750 | UDP | Kerberos | Kerberos legacy. |
|  751 | TCP | Kerberos password | Service historique. |
|  753 | TCP | RRDP | Remote RWhois. |
|  754 | TCP | Tell | Service historique. |
|  760 | TCP | Kerberos | Service legacy. |
|  765 | TCP | Webster | Service historique. |
|  767 | TCP | Phone | Service historique. |
|  772 | TCP | COPS | Common Open Policy Service. |
|  774 | TCP | Rpasswd | Service historique. |
|  777 | TCP | Multiling HTTP | Port alternatif souvent utilisé par applications. |
|  783 | TCP | SpamAssassin | Filtrage anti-spam daemon. |
|  800 | TCP | HTTP alternate | Port web alternatif. |
|  801 | TCP | HTTP alternate | Port alternatif, usage applicatif. |
|  808 | TCP | HTTP alternate | Web alternatif fréquemment rencontré. |
|  843 | TCP | Flash policy | Ancien service de politique Flash. |
|  873 | TCP | rsync | Synchronisation de fichiers rsync daemon. |
|  880 | TCP | HTTP alternate | Port alternatif web. |
|  888 | TCP | HTTP alternate | Port web alternatif courant. |
|  902 | TCP/UDP | VMware | Console/communication VMware selon version. |
|  903 | TCP | VMware | Console VMware legacy. |
|  908 | TCP | HTTP alternate | Web alternatif. |
|  911 | TCP | HTTP alternate | Web alternatif. |
|  912 | TCP | VMware | Service VMware. |
|  989 | TCP | FTPS-data | Données FTP TLS implicite. |
|  990 | TCP | FTPS-control | Contrôle FTP TLS implicite. |
|  992 | TCP | Telnet TLS | Telnet sécurisé (legacy). |
|  993 | TCP | IMAPS | IMAP TLS implicite. |
|  994 | TCP | IRCS | IRC TLS (assignation historique). |
|  995 | TCP | POP3S | POP3 TLS implicite. |
|  1000 | TCP | Web alternate | Port applicatif alternatif. |
|  1023 | TCP/UDP | Réserve fin ports système | Limite de plage well-known. |
|  1024 | TCP/UDP | Port système/privileged boundary | Début de la plage utilisateur/registered. |
|  1025 | TCP | Microsoft RPC | Port dynamique RPC fréquemment vu sur Windows ancien. |
|  1026 | TCP | Microsoft RPC | Port dynamique RPC fréquent. |
|  1027 | TCP | Microsoft RPC | Port dynamique RPC fréquent. |
|  1028 | TCP | Microsoft RPC | Port dynamique RPC fréquent. |
|  1029 | TCP | Microsoft RPC | Port dynamique RPC fréquent. |
|  1030 | TCP | Microsoft RPC | Port dynamique RPC fréquent. |
|  1033 | TCP | Netinfo | Service historique. |
|  1040 | TCP | Netscaler | Port applicatif selon configuration. |
|  1041 | TCP | Netscaler | Port applicatif selon configuration. |
|  1042 | TCP | Netscaler | Port applicatif selon configuration. |
|  1043 | TCP | Netscaler | Port applicatif selon configuration. |
|  1044 | TCP | Netscaler | Port applicatif selon configuration. |
|  1050 | TCP | Java RMI | RMI registry/communications selon configuration. |
|  1053 | TCP/UDP | DNS alternate | DNS alternatif. |
|  1054 | TCP | Adobe | Service historique. |
|  1058 | TCP | Nim | Service historique. |
|  1060 | TCP | PO | Service legacy. |
|  1066 | TCP | SQLNet | Service Oracle legacy. |
|  1080 | TCP | SOCKS proxy | Proxy SOCKS. |
|  1090 | TCP | SOCKS proxy alternate | Proxy alternatif. |
|  1098 | TCP | Java RMI | Service RMI. |
|  1099 | TCP | Java RMI Registry | Registre RMI Java. |
|  1100 | TCP | Java RMI | Port RMI courant dans certaines configurations. |
|  1109 | TCP | KPOP | POP Kerberos legacy. |
|  1110 | TCP | POP3 alternate | POP3 alternatif. |
|  1111 | TCP | Port applicatif | Port souvent choisi par applications de test. |
|  1120 | TCP | Port applicatif | Service spécifique selon configuration. |
|  1123 | TCP | MSSQL | Port alternatif SQL Server dans certains environnements. |
|  1158 | TCP | Oracle EM | Interface Oracle Enterprise Manager (ancienne). |
|  1194 | UDP/TCP | OpenVPN | VPN OpenVPN, port par défaut fréquent. |
|  1195 | UDP | OpenVPN alternate | Port alternatif. |
|  1214 | TCP | Kazaa | P2P historique. |
|  1234 | TCP/UDP | Port applicatif | Port fréquemment utilisé pour tests/services locaux. |
|  1241 | TCP | Nessus | Interface/communication Nessus historique. |
|  1270 | TCP | MOM | Microsoft Operations Manager legacy. |
|  1311 | TCP | Dell OpenManage | Administration serveur Dell. |
|  1337 | TCP | Leet / custom | Port non officiel populaire pour services personnalisés. |
|  1352 | TCP | Lotus Notes | Lotus Notes/Domino. |
|  1414 | TCP | IBM MQ | Messaging IBM MQ. |
|  1433 | TCP | Microsoft SQL Server | Base de données SQL Server. |
|  1434 | UDP | SQL Server Browser | Découverte instances SQL Server. |
|  1434 | TCP | SQL Server | Port alternatif selon configuration. |
|  1494 | TCP | Citrix ICA | Sessions Citrix. |
|  1500 | TCP | VLS | Service historique. |
|  1521 | TCP | Oracle Listener | Connexion Oracle DB. |
|  1522 | TCP | Oracle alternate | Port Oracle alternatif. |
|  1524 | TCP | ingreslock | Service legacy; parfois repéré dans anciens labs. |
|  1525 | TCP | Oracle alternate | Port alternatif Oracle. |
|  1533 | TCP | Sametime | IBM Sametime legacy. |
|  1583 | TCP | Pervasive SQL | Base Pervasive. |
|  1604 | TCP/UDP | Citrix | Service Citrix legacy. |
|  1645 | UDP | RADIUS auth (legacy) | Authentification RADIUS ancien port. |
|  1646 | UDP | RADIUS accounting (legacy) | Accounting RADIUS ancien port. |
|  1701 | UDP | L2TP | Tunnel L2TP. |
|  1720 | TCP | H.323 | Signalisation H.323. |
|  1723 | TCP | PPTP | VPN PPTP (obsolète, sécurité faible). |
|  1755 | TCP/UDP | MMS | Microsoft Media Services legacy. |
|  1761 | TCP | Oracle | Service Oracle legacy. |
|  1801 | TCP/UDP | MSMQ | Microsoft Message Queuing. |
|  1812 | UDP | RADIUS auth | Authentification RADIUS. |
|  1813 | UDP | RADIUS accounting | Comptabilisation RADIUS. |
|  1863 | TCP | MSN Messenger | Service messagerie legacy. |
|  1883 | TCP | MQTT | IoT messaging sans TLS. |
|  1900 | UDP | SSDP | Découverte UPnP. |
|  1935 | TCP | RTMP | Streaming/média (legacy). |
|  1962 | TCP | PTC | Service industriel/application. |
|  1972 | TCP | Caché | Base Caché/InterSystems. |
|  1984 | TCP | Big Brother | Supervision legacy. |
|  1998 | TCP | Cisco X.25 | Service historique. |
|  2000 | TCP/UDP | Cisco SCCP | VoIP Cisco Skinny. |
|  2001 | TCP | DC | Port applicatif fréquemment utilisé. |
|  2002 | TCP | DC | Port applicatif fréquemment utilisé. |
|  2003 | TCP | Graphite | Graphite carbon/metrics. |
|  2004 | TCP | Graphite | Graphite receiver selon configuration. |
|  2005 | TCP | Cisco SCCP | VoIP Cisco. |
|  2008 | TCP | Port applicatif | Usage variable. |
|  2010 | TCP | Port applicatif | Usage variable. |
|  2020 | TCP | FTP alternate | FTP alternatif. |
|  2021 | TCP | FTP alternate | FTP alternatif. |
|  2022 | TCP | SSH alternate | SSH sur port non standard. |
|  2030 | TCP | Port applicatif | Usage variable. |
|  2049 | TCP/UDP | NFS | Partage de fichiers NFS. |
|  2050 | TCP | Port applicatif | Usage variable. |
|  2082 | TCP | cPanel | Interface cPanel non TLS. |
|  2083 | TCP | cPanel SSL | Interface cPanel TLS. |
|  2086 | TCP | WHM | WebHost Manager non TLS. |
|  2087 | TCP | WHM SSL | WHM TLS. |
|  2095 | TCP | Webmail | Webmail non TLS. |
|  2096 | TCP | Webmail SSL | Webmail TLS. |
|  2100 | TCP | Oracle XDB | Oracle XML DB/FTP selon config. |
|  2101 | TCP | NFS alternate | Service alternatif. |
|  2102 | TCP | Zephyr | Zephyr notification. |
|  2103 | TCP | Zephyr | Zephyr server. |
|  2104 | TCP | Zephyr | Zephyr client. |
|  2121 | TCP | FTP alternate | FTP sur port alternatif. |
|  2144 | TCP | Port applicatif | Usage variable. |
|  2152 | UDP | GTP-U | Tunnel de données mobile. |
|  2181 | TCP | ZooKeeper | Coordination cluster Apache ZooKeeper. |
|  2200 | TCP | SSH alternate | Port SSH alternatif courant. |
|  2222 | TCP | SSH alternate | Port alternatif souvent choisi. |
|  2223 | TCP | Port applicatif | Usage variable. |
|  2251 | TCP | Cisco | Service historique. |
|  2301 | TCP | Compaq Insight | Administration serveur legacy. |
|  2323 | TCP | Telnet alternate | Telnet alternatif (non chiffré). |
|  2375 | TCP | Docker API | API Docker non TLS (à ne pas exposer). |
|  2376 | TCP | Docker TLS | API Docker TLS. |
|  2377 | TCP | Docker Swarm | Gestion cluster Swarm. |
|  2379 | TCP | etcd client | API client etcd. |
|  2380 | TCP | etcd peer | Communication entre membres etcd. |
|  2399 | TCP | FileMaker | Service FileMaker. |
|  2401 | TCP | CVS | Concurrent Versions System. |
|  2404 | TCP | IEC-104 | Protocole industriel téléconduite. |
|  2427 | UDP | MGCP | Media Gateway Control. |
|  2443 | TCP | HTTPS alternate | Port TLS alternatif. |
|  2483 | TCP | Oracle TCPS | Oracle sur TLS. |
|  2484 TCP | Oracle TCPS | Oracle sécurisé (port souvent utilisé). |
|  2500 | TCP | RPC | Port applicatif/RPC variable. |
|  2525 | TCP | SMTP alternate | Soumission SMTP alternative. |
|  2546 | TCP | Port applicatif | Usage variable. |
|  2598 | TCP | Citrix | Citrix Session Reliability. |
|  2601 | TCP | Zebra | Routage Zebra legacy. |
|  2604 | TCP | BGPd | Gestion routeur/quagga legacy. |
|  2638 | TCP | SQL Anywhere | Base SQL Anywhere. |
|  2700 | TCP | Port applicatif | Usage variable. |
|  2701 | TCP | SMS | Microsoft SMS legacy. |
|  2702 | TCP | SMS | Microsoft SMS legacy. |
|  2703 | TCP | SMS | Microsoft SMS legacy. |
|  2704 | TCP | SMS | Microsoft SMS legacy. |
|  2705 | TCP | SMS | Microsoft SMS legacy. |
|  2706 | TCP | SMS | Microsoft SMS legacy. |
|  2707 | TCP | SMS | Microsoft SMS legacy. |
|  2708 | TCP | SMS | Microsoft SMS legacy. |
|  2709 | TCP | SMS | Microsoft SMS legacy. |
|  2710 | TCP | SMS | Microsoft SMS legacy. |
|  2717 | TCP | PNMS | Service legacy. |
|  2800 | TCP | HTTP alternate | Port web alternatif. |
|  2809 | TCP | CORBA | Naming service CORBA. |
|  2811 | TCP | GSI FTP | GridFTP service. |
|  2869 TCP | UPnP | UPnP eventing HTTP | Découverte/contrôle UPnP. |
|  2875 | TCP | Port applicatif | Usage variable. |
|  3000 | TCP | Dev/web apps | Port web/dev très fréquent. |
|  3001 | TCP | Web alternate | Web alternatif. |
|  3002 | TCP | Web alternate | Web alternatif. |
|  3003 | TCP | Web alternate | Web alternatif. |
|  3004 | TCP | Web alternate | Web alternatif. |
|  3005 | TCP | Web alternate | Web alternatif. |
|  3006 | TCP | Web alternate | Web alternatif. |
|  3007 | TCP | Web alternate | Web alternatif. |
|  3008 | TCP | Web alternate | Web alternatif. |
|  3009 | TCP | Web alternate | Web alternatif. |
|  3010 | TCP | Web alternate | Web alternatif. |
|  3030 | TCP | Web alternate | Web alternatif. |
|  3050 | TCP | Firebird | Base Firebird. |
|  3074 | TCP/UDP | Xbox Live | Jeux/communications Xbox. |
|  3128 | TCP | Squid proxy | Proxy HTTP Squid fréquent. |
|  3129 | TCP | Proxy alternate | Proxy alternatif. |
|  3130 | TCP | ICP | Internet Cache Protocol. |
|  3260 | TCP | iSCSI | Stockage réseau iSCSI. |
|  3268 | TCP | LDAP Global Catalog | Catalogue global Active Directory. |
|  3269 | TCP | LDAPS Global Catalog | Catalogue global AD sur TLS. |
|  3300 | TCP | Port applicatif | Usage variable. |
|  3306 | TCP | MySQL/MariaDB | Base de données MySQL/MariaDB. |
|  3307 | TCP | MySQL alternate | Port DB alternatif. |
|  3310 | TCP | ClamAV | ClamAV daemon (clamd). |
|  3333 | TCP | Port applicatif | Port souvent utilisé par services/tests. |
|  3389 | TCP/UDP | RDP | Bureau distant Windows. |
|  3390 | TCP | RDP alternate | RDP port alternatif. |
|  3400 | TCP | Port applicatif | Usage variable. |
|  3478 | TCP/UDP | STUN/TURN | Traversée NAT et média temps réel. |
|  3479 | TCP/UDP | TURN alternate | Services traversée NAT. |
|  3500 | TCP | Port applicatif | Usage variable. |
|  3544 | UDP | Teredo | Tunnel IPv6 Teredo. |
|  3632 | TCP | distcc | Compilation distribuée. |
|  3690 | TCP | SVN | Subversion version control. |
|  3702 | UDP | WS-Discovery | Découverte de services sur LAN. |
|  3724 | TCP | Blizzard | Jeux/launcher historique. |
|  3784 | UDP | BFD | Détection rapide de défaillance de routage. |
|  3785 | UDP | BFD | BFD selon mode/config. |
|  3800 | TCP | Port applicatif | Usage variable. |
|  4000 | TCP | Web alternate | Port applicatif/web courant. |
|  4001 | TCP | Web alternate | Port alternatif. |
|  4040 | TCP | Spark | Interface Spark (souvent web). |
|  4060 | TCP | Port applicatif | Usage variable. |
|  4080 | TCP | Web alternate | Port web alternatif. |
|  4100 | TCP | Web alternate | Port web alternatif. |
|  4111 | TCP | Xgrid | Service Apple legacy. |
|  4125 | TCP | Port applicatif | Usage variable. |
|  4200 | TCP | Web dev | Serveur de développement web fréquent. |
|  4222 | TCP | NATS | Messaging NATS. |
|  4242 | TCP | Port applicatif | Port populaire de service/test. |
|  4300 | TCP | Web alternate | Port web alternatif. |
|  4321 | TCP | Rwhois | Service historique. |
|  4443 | TCP | HTTPS alternate | HTTPS sur port alternatif. |
|  4444 | TCP | Port applicatif | Port souvent utilisé par outils/tests; service variable. |
|  4445 | TCP | Port applicatif | Usage variable. |
|  4500 | UDP | IPsec NAT-T | Tunnel IPsec à travers NAT. |
|  4567 | TCP | Port applicatif | Usage variable. |
|  4662 | TCP | eDonkey | P2P legacy. |
|  4672 | UDP | eMule | P2P legacy. |
|  4711 | TCP | Port applicatif | Usage variable. |
|  4789 | UDP | VXLAN | Overlay réseau VXLAN. |
|  4848 | TCP | GlassFish | Administration GlassFish. |
|  4899 | TCP | Radmin | Administration distante Radmin. |
|  5000 | TCP | Flask/dev/web | Port web/dev fréquent; service dépendant. |
|  5001 | TCP | HTTPS alternate | Web/TLS alternatif; aussi iPerf selon configuration. |
|  5002 | TCP | Port applicatif | Usage variable. |
|  5003 | TCP | FileMaker | FileMaker service. |
|  5004 | UDP | RTP | Média RTP (configuration). |
|  5005 | UDP | RTCP | Contrôle média RTCP. |
|  5006 | TCP | Port applicatif | Usage variable. |
|  5007 | TCP | Port applicatif | Usage variable. |
|  5010 | TCP | Port applicatif | Usage variable. |
|  5060 | TCP/UDP | SIP | Signalisation VoIP. |
|  5061 | TCP | SIP-TLS | Signalisation SIP chiffrée. |
|  5090 | TCP/UDP | SIP alternate | SIP alternatif. |
|  5100 | TCP | X11 alternate | X11 alternatif. |
|  5140 | TCP | Syslog alternate | Journaux alternatif. |
|  5150 | TCP | Port applicatif | Usage variable. |
|  5200 | TCP | Port applicatif | Usage variable. |
|  5201 | TCP/UDP | iperf3 | Mesure de débit réseau. |
|  5222 | TCP | XMPP client | Messagerie XMPP. |
|  5223 | TCP | XMPP TLS legacy | XMPP TLS historique. |
|  5269 | TCP | XMPP server | Connexions serveur XMPP. |
|  5280 | TCP | XMPP HTTP | Interface/HTTP XMPP. |
|  5298 | TCP | XMPP | Service XMPP legacy. |
|  5353 | UDP | mDNS | Découverte multicast DNS locale. |
|  5355 | UDP | LLMNR | Résolution locale de noms. |
|  5432 | TCP | PostgreSQL | Base de données PostgreSQL. |
|  5433 | TCP | PostgreSQL alternate | Port PostgreSQL alternatif. |
|  5500 | TCP | VNC alternate | VNC/port applicatif selon config. |
|  5554 | TCP | RTSP alternate | Port média/RTSP alternatif. |
|  5555 | TCP | Android Debug Bridge | ADB TCP (si activé). |
|  5601 | TCP | Kibana | Interface Kibana web. |
|  5631 | TCP | PCAnywhere | Remote access legacy. |
|  5632 | UDP | PCAnywhere | Remote access legacy. |
|  5666 | TCP | NRPE | Nagios Remote Plugin Executor. |
|  5671 | TCP | AMQP TLS | Messaging AMQP TLS. |
|  5672 | TCP | AMQP | Messaging RabbitMQ/AMQP. |
|  5683 | UDP | CoAP | IoT REST-like protocol. |
|  5684 | UDP | CoAP TLS/DTLS | CoAP sécurisé. |
|  5700 | TCP | VNC alternate | Port VNC alternatif. |
|  5800 | TCP | VNC web | Interface web VNC (configuration). |
|  5900 | TCP | VNC | Bureau distant VNC. |
|  5901 | TCP | VNC display 1 | VNC display/port additionnel. |
|  5902 | TCP | VNC display 2 | VNC display/port additionnel. |
|  5903 | TCP | VNC display 3 | VNC display/port additionnel. |
|  5984 | TCP | CouchDB | API CouchDB. |
|  5985 | TCP | WinRM HTTP | Administration Windows via HTTP. |
|  5986 | TCP | WinRM HTTPS | Administration Windows via HTTPS. |
|  6000 | TCP | X11 | X Window System (display 0). |
|  6001 | TCP | X11 display 1 | X11 display 1. |
|  6002 | TCP | X11 display 2 | X11 display 2. |
|  6003 | TCP | X11 display 3 | X11 display 3. |
|  6004 | TCP | X11 display 4 | X11 display 4. |
|  6005 | TCP | X11 display 5 | X11 display 5. |
|  6006 | TCP | X11 display 6 | X11 display 6. |
|  6007 | TCP | X11 display 7 | X11 display 7. |
|  6008 | TCP | X11 display 8 | X11 display 8. |
|  6009 | TCP | X11 display 9 | X11 display 9. |
|  6010 | TCP | X11 display 10 | X11 display 10. |
|  6060 | TCP | Web alternate | Port web/app alternatif. |
|  6061 | TCP | Web alternate | Port web/app alternatif. |
|  6379 | TCP | Redis | Cache/clé-valeur Redis. |
|  6443 | TCP | Kubernetes API | API Kubernetes souvent TLS. |
|  6500 | TCP | Port applicatif | Usage variable. |
|  6514 | TCP | Syslog TLS | Syslog sécurisé TLS. |
|  6543 | TCP | PostgreSQL alternate | Port DB alternatif. |
|  6660–6669 | TCP | IRC | Ports IRC historiques. |
|  6679 | TCP | IRC alternate | IRC alternatif. |
|  6697 | TCP | IRC TLS | IRC sécurisé. |
|  6881 | TCP/UDP | BitTorrent | P2P BitTorrent (port historique). |
|  6969 | TCP/UDP | BitTorrent tracker | Tracker BitTorrent fréquent. |
|  7000 | TCP | Web alternate | Port web/app alternatif. |
|  7001 | TCP | WebLogic | WebLogic admin/application. |
|  7002 | TCP | WebLogic TLS | WebLogic sécurisé. |
|  7003 | TCP | Web alternate | Port web alternatif. |
|  7070 | TCP | RTSP/HTTP alternate | Média/HTTP selon service. |
|  7100 | TCP | X font server | Service fonts X legacy. |
|  7199 | TCP | Cassandra JMX | Gestion Cassandra JMX (config). |
|  7200 | TCP | Port applicatif | Usage variable. |
|  7443 | TCP | HTTPS alternate | HTTPS alternatif. |
|  7474 | TCP | Neo4j HTTP | Interface/API Neo4j. |
|  7687 | TCP | Neo4j Bolt | Protocole Bolt Neo4j. |
|  7777 | TCP | Port applicatif | Port fréquemment utilisé par applications. |
|  7800 | TCP | Port applicatif | Usage variable. |
|  8000 | TCP | HTTP alternate | Serveur web/dev, proxy, API. |
|  8001 | TCP | HTTP alternate | Web/API alternatif. |
|  8002 | TCP | HTTP alternate | Web/API alternatif. |
|  8003 | TCP | HTTP alternate | Web/API alternatif. |
|  8004 | TCP | HTTP alternate | Web/API alternatif. |
|  8005 | TCP | Tomcat shutdown | Port de shutdown Tomcat (local/config). |
|  8006 | TCP | Proxmox web | Interface Proxmox VE. |
|  8007 | TCP | HTTP alternate | Port web alternatif. |
|  8008 | TCP | HTTP alternate | HTTP alternatif. |
|  8009 | TCP | AJP | Apache JServ Protocol/Tomcat. |
|  8010 | TCP | HTTP alternate | Port web alternatif. |
|  8020 | TCP | Hadoop | Hadoop namenode/IPC selon config. |
|  8030 | TCP | Hadoop | Service Hadoop. |
|  8040 | TCP | Hadoop | Service Hadoop. |
|  8042 | TCP | Hadoop YARN | NodeManager web UI. |
|  8080 | TCP | HTTP proxy/web alternate | Web, proxy, admin ou API. |
|  8081 | TCP | HTTP alternate | Port web/API alternatif. |
|  8082 | TCP | HTTP alternate | Port web/API alternatif. |
|  8083 | TCP | HTTP alternate | Port web/API alternatif. |
|  8084 | TCP | HTTP alternate | Port web/API alternatif. |
|  8085 | TCP | HTTP alternate | Port web/API alternatif. |
|  8086 | TCP | InfluxDB | API InfluxDB HTTP. |
|  8087 | TCP | HTTP alternate | Port web alternatif. |
|  8088 | TCP | Hadoop YARN | ResourceManager web UI. |
|  8089 | TCP | HTTP alternate | Port web alternatif. |
|  8090 | TCP | HTTP alternate | Web/app alternatif. |
|  8091 | TCP | Couchbase | Couchbase service/UI selon configuration. |
|  8092 | TCP | HTTP alternate | Port web alternatif. |
|  8093 | TCP | Couchbase | Service Couchbase. |
|  8094 | TCP | Couchbase | Service Couchbase. |
|  8095 | TCP | HTTP alternate | Port web alternatif. |
|  8096 | TCP | Jellyfin | Media server web/API. |
|  8097 | TCP | HTTP alternate | Port web alternatif. |
|  8098 | TCP | HTTP alternate | Port web alternatif. |
|  8099 | TCP | HTTP alternate | Port web alternatif. |
|  8100 | TCP | HTTP alternate | Port web/app alternatif. |
|  8111 | TCP | HTTP alternate | Web/app; JetBrains TeamCity par défaut. |
|  8123 | TCP | Home Assistant | Interface/API Home Assistant. |
|  8125 | UDP | StatsD | Collecte métriques StatsD. |
|  8139 | TCP | HTTP alternate | Port alternatif. |
|  8161 | TCP | ActiveMQ | Console web ActiveMQ. |
|  8180 | TCP | HTTP alternate | Web/app alternatif. |
|  8181 | TCP | HTTP alternate | Web/app fréquent. |
|  8200 | TCP | HashiCorp Vault | API Vault. |
|  8222 | TCP | NATS | Monitoring NATS ou port configuré. |
|  8243 | TCP | HTTPS alternate | HTTPS web alternatif. |
|  8280 | TCP | HTTP alternate | Port web alternatif. |
|  8282 | TCP | HTTP alternate | Port web/app alternatif. |
|  8291 | TCP | MikroTik Winbox | Administration MikroTik. |
|  8333 | TCP | Bitcoin | Peer-to-peer Bitcoin. |
|  8334 | TCP | Bitcoin | Port applicatif Bitcoin alternatif. |
|  8383 | TCP | HTTP alternate | Web/app alternatif. |
|  8400 | TCP | Port applicatif | Usage variable. |
|  8443 | TCP | HTTPS alternate | Web TLS alternatif, admin/API. |
|  8444 | TCP | HTTPS alternate | Port TLS alternatif. |
|  8500 | TCP | Consul | API/UI Consul. |
|  8530 | TCP | WSUS HTTP | Windows Update Services HTTP. |
|  8531 | TCP | WSUS HTTPS | WSUS TLS. |
|  8554 | TCP | RTSP alternate | Streaming RTSP alternatif. |
|  8600 | TCP/UDP | Consul DNS | DNS Consul (config). |
|  8649 | TCP | Ganglia | Monitoring Ganglia. |
|  8686 | TCP | JMX | Gestion Java (config). |
|  8761 | TCP | Eureka | Service registry Spring Eureka. |
|  8880 | TCP | HTTP alternate | Port web alternatif. |
|  8881 | TCP | HTTP alternate | Port web alternatif. |
|  8882 | TCP | HTTP alternate | Port web alternatif. |
|  8883 | TCP | MQTT TLS | MQTT sécurisé. |
|  8888 | TCP | HTTP alternate | Web notebook, proxy, app/dev. |
|  8889 | TCP | HTTP alternate | Web/app alternatif. |
|  8890 | TCP | HTTP alternate | Web/app alternatif. |
|  8900 | TCP | Port applicatif | Usage variable. |
|  9000 | TCP | HTTP alternate | Web/app, dashboards, API. |
|  9001 | TCP | Tor OR alternate / app | Port variable; Tor relay souvent configuré. |
|  9002 | TCP | HTTP alternate | Web/app alternatif. |
|  9003 | TCP | Xdebug | Debug PHP (configuration). |
|  9004 | TCP | HTTP alternate | Port web/app alternatif. |
|  9005 | TCP | HTTP alternate | Port web/app alternatif. |
|  9006 | TCP | HTTP alternate | Port web/app alternatif. |
|  9009 | TCP | AJP alternate | Service AJP/application selon config. |
|  9042 | TCP | Cassandra CQL | Cassandra client. |
|  9050 | TCP | Tor SOCKS | Proxy SOCKS Tor (configuration courante). |
|  9051 | TCP | Tor control | Interface de contrôle Tor (à protéger). |
|  9060 | TCP | HTTP alternate | Web/app alternatif. |
|  9080 | TCP | HTTP alternate | Web/app alternatif. |
|  9090 | TCP | Prometheus | Monitoring Prometheus UI/API. |
|  9091 | TCP | Transmission | Interface Transmission; aussi Prometheus selon config. |
|  9092 | TCP | Kafka | Kafka broker. |
|  9093 | TCP | Kafka | Kafka/coordination selon configuration. |
|  9094 | TCP | Kafka | Kafka alternatif. |
|  9100 | TCP | JetDirect | Impression réseau. |
|  9101 | TCP | Bacula | Bacula director/worker selon rôle. |
|  9102 | TCP | Bacula | Bacula file daemon. |
|  9103 | TCP | Bacula | Bacula storage daemon. |
|  9110 | TCP | HTTP alternate | Web/app alternatif. |
|  9111 | TCP | HTTP alternate | Web/app alternatif. |
|  9160 | TCP | Cassandra | Service Cassandra alternatif. |
|  9200 | TCP | Elasticsearch | API HTTP Elasticsearch. |
|  9201 | TCP | Elasticsearch alternate | Port cluster/API alternatif. |
|  9300 | TCP | Elasticsearch transport | Communication cluster Elasticsearch. |
|  9418 | TCP | Git | Protocole Git natif. |
|  9443 | TCP | HTTPS alternate | Web TLS alternatif. |
|  9444 | TCP | HTTPS alternate | Web TLS alternatif. |
|  9500 | TCP | Port applicatif | Usage variable. |
|  9530 | TCP | DNS management | Port applicatif DNS selon config. |
|  9535 | TCP | mDNS alternate | Service applicatif. |
|  9600 | TCP | Logstash | API monitoring Logstash. |
|  9666 | TCP | Port applicatif | Usage variable. |
|  9876 | TCP | Port applicatif | Usage variable. |
|  9898 | TCP | HTTP alternate | Web/app alternatif. |
|  9900 | TCP | Port applicatif | Usage variable. |
|  9990 | TCP | WildFly management | Interface gestion WildFly. |
|  9999 | TCP | HTTP alternate | Web/app/debug alternatif. |
|  10000 | TCP | Webmin | Administration Webmin (configuration). |
|  10001 | TCP | Webmin alternate | Port alternatif. |
|  10050 | TCP | Zabbix agent | Agent Zabbix. |
|  10051 | TCP | Zabbix server | Réception Zabbix. |
|  10080 | TCP | HTTP alternate | Port web alternatif. |
|  10100 | TCP | Port applicatif | Usage variable. |
|  10250 | TCP | Kubernetes kubelet | API kubelet. |
|  10255 | TCP | Kubernetes kubelet read-only (legacy) | Endpoint historique, souvent désactivé. |
|  10443 | TCP | HTTPS alternate | TLS web alternatif. |
|  10500 | TCP | Port applicatif | Usage variable. |
|  11211 | TCP/UDP | Memcached | Cache mémoire Memcached. |
|  11371 TCP | HKP | Serveur de clés OpenPGP | HTTP Keyserver Protocol (port historique). |
|  12000 | TCP | Port applicatif | Usage variable. |
|  12345 | TCP | NetBus (historique) | Port associé à un ancien outil malveillant; usage actuel variable. |
|  13000 | TCP | Port applicatif | Usage variable. |
|  13306 | TCP | MySQL alternate | MySQL port alternatif. |
|  14330 | TCP | MSSQL alternate | SQL Server alternatif. |
|  15000 | TCP | Port applicatif | Usage variable. |
|  15672 | TCP | RabbitMQ management | Interface de gestion RabbitMQ. |
|  16000 | TCP | Port applicatif | Usage variable. |
|  17000 | TCP | Port applicatif | Usage variable. |
|  18080 | TCP | HTTP alternate | Web/app alternatif. |
|  18181 | TCP | HTTP alternate | Web/app alternatif. |
|  19000 | TCP | Port applicatif | Usage variable. |
|  20000 | TCP | DNP3 | Protocole industriel DNP3 (port fréquent). |
|  20001 | TCP | Port applicatif | Usage variable. |
|  20443 | TCP | HTTPS alternate | Port TLS alternatif. |
|  21000 | TCP | Port applicatif | Usage variable. |
|  22000 | TCP | Syncthing | Synchronisation Syncthing. |
|  22100 | TCP | Port applicatif | Usage variable. |
|  22222 | TCP | Port applicatif | Port custom courant. |
|  23000 | TCP | Port applicatif | Usage variable. |
|  23700 | TCP | Port applicatif | Usage variable. |
|  24000 | TCP | Port applicatif | Usage variable. |
|  25000 | TCP | Port applicatif | Usage variable. |
|  25565 | TCP | Minecraft Java | Serveur Minecraft Java (port par défaut). |
|  27000 | TCP | FlexLM | Gestion licences FlexNet (plage/config). |
|  27015 | TCP/UDP | Steam / Source | Jeux, serveur et query selon configuration. |
|  27017 | TCP | MongoDB | Base MongoDB. |
|  27018 | TCP | MongoDB alternate | MongoDB shard/port alternatif. |
|  27019 | TCP | MongoDB config | MongoDB config server. |
|  28000 | TCP | Port applicatif | Usage variable. |
|  28017 | TCP | MongoDB web legacy | Ancienne interface HTTP MongoDB, obsolète. |
|  30000 | TCP | Port applicatif | Usage variable; aussi plage NodePort Kubernetes. |
|  30001 | TCP | Kubernetes NodePort | Port NodePort possible (plage par défaut 30000–32767). |
|  30080 | TCP | Kubernetes NodePort | NodePort fréquent pour HTTP. |
|  30443 | TCP | Kubernetes NodePort | NodePort fréquent pour HTTPS. |
|  31000 | TCP | Kubernetes NodePort | NodePort possible. |
|  32000 | TCP | Kubernetes NodePort | NodePort possible. |
|  32764 | TCP | Router backdoor (reports historiques) | Port signalé sur certains équipements anciens; ne pas présumer. |
|  33000 | TCP | Port applicatif | Usage variable. |
|  33890 | TCP | RDP alternate | Port RDP personnalisé. |
|  35000 | TCP | Port applicatif | Usage variable. |
|  37000 | TCP | Port applicatif | Usage variable. |
|  40000 | TCP | Port applicatif | Usage variable. |
|  41000 | TCP | Port applicatif | Usage variable. |
|  42000 | TCP | Port applicatif | Usage variable. |
|  43000 | TCP | Port applicatif | Usage variable. |
|  44000 | TCP | Port applicatif | Usage variable. |
|  45000 | TCP | Port applicatif | Usage variable. |
|  46000 | TCP | Port applicatif | Usage variable. |
|  47000 | TCP | Port applicatif | Usage variable. |
|  48000 | TCP | Port applicatif | Usage variable. |
|  49152 | TCP/UDP | Début ports dynamiques | Début de la plage éphémère courante Windows/IANA. |
|  49153–65535 | TCP/UDP | Ports dynamiques/privés | Ports éphémères choisis pour connexions client et services temporaires; pas de service fixe. |

## Références

- [IANA Service Name and Transport Protocol Port Number Registry](https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml)
- [RFC 6335 — Service Name and Port Number Procedures](https://www.rfc-editor.org/rfc/rfc6335)
- [RFC 6056 — Recommendations for Transport Protocol Port Randomization](https://www.rfc-editor.org/rfc/rfc6056)
