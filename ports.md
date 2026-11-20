# Catalogue des ports réseau

> Ports TCP/UDP classés par numéro croissant. Le numéro de port ne garantit pas le service : un service peut être configuré sur un autre port et un port peut être réutilisé. Cette première version liste les ports connus, courants et importants, pas la totalité des enregistrements IANA ni les 65 536 numéros.
>
> Plages : **0–1023** ports système/well-known; **1024–49151** ports enregistrés; **49152–65535** ports dynamiques/éphémères (plage courante, variable selon OS).

| Port | Protocole | Nom / service | Utilité |
|---:|---|---|---|
| 0 | TCP/UDP | Reserved | Port réservé ; utilisé notamment pour la désignation d'un port source dans certains contextes. |
| 1 | TCP/UDP | tcpmux | TCP Port Service Multiplexer. |
| 2 | TCP/UDP | Reserved | Ancien port CompressNET, désattribué et réservé. |
| 3 | TCP/UDP | Reserved | Ancien port CompressNET, désattribué et réservé. |
| 4 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 5 | TCP/UDP | rje | Remote Job Entry. |
| 6 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 7 | TCP/UDP | echo | Echo : renvoie les données reçues. |
| 8 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 9 | TCP/UDP | discard | Discard : ignore les données reçues. |
| 10 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 11 | TCP/UDP | systat | Active Users : informations sur les utilisateurs actifs. |
| 12 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 13 | TCP/UDP | daytime | Service donnant la date et l'heure. |
| 14 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 15 | TCP | Unassigned | Ancien netstat, désormais non attribué. |
| 16 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 17 | TCP/UDP | qotd | Quote of the Day : citation du jour. |
| 18 | TCP/UDP | msp | Message Send Protocol (historique). |
| 19 | TCP/UDP | chargen | Character Generator : générateur de caractères. |
| 20 | TCP/UDP | ftp-data | FTP — canal de transfert de données. |
| 21 | TCP/UDP | ftp | FTP — canal de contrôle. |
| 22 | TCP/UDP | ssh | Secure Shell : connexion distante sécurisée. |
| 23 | TCP/UDP | telnet | Telnet : accès distant non chiffré. |
| 24 | TCP | Unassigned | Ancien service Any Private Mail System ; attribution historique. |
| 25 | TCP/UDP | smtp | Simple Mail Transfer Protocol : transfert de courrier électronique. |
| 26 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 27 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 28 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 29 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 30 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 31 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 32 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 33 | TCP | dsp | Display Support Protocol. |
| 34 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 35 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 36 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 37 | TCP/UDP | time | Time Protocol : service de synchronisation horaire historique. |
| 38 | TCP | rap | Route Access Protocol. |
| 39 | TCP/UDP | rlp | Resource Location Protocol. |
| 40 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 41 | TCP/UDP | graphics | Graphics : service graphique historique. |
| 42 | TCP/UDP | nameserver | Host Name Server, service historique de résolution de noms. |
| 43 | TCP | nicname | WHOIS : interrogation d'informations sur les domaines et enregistrements. |
| 44 | TCP | mpm-flags | MPM FLAGS Protocol. |
| 45 | TCP | mpm | Message Processing Module — réception. |
| 46 | TCP/UDP | mpm-snd | Message Processing Module — émission. |
| 47 | TCP/UDP | Reserved | Ancien port réservé, entrée retirée du registre. |
| 48 | TCP/UDP | auditd | Digital Audit Daemon. |
| 49 | TCP/UDP | tacacs | TACACS : protocole d'authentification, d'autorisation et de comptabilité. |
| 50 | TCP/UDP | re-mail-ck | Remote Mail Checking Protocol. |
| 51 | — | Reserved | Ancienne attribution LA-MAINT ; statut historique/réservé. |
| 52 | TCP/UDP | xns-time | XNS Time Protocol. |
| 53 | TCP/UDP | domain | DNS : Domain Name System. |
| 54 | TCP/UDP | xns-ch | XNS Clearinghouse. |
| 55 | TCP/UDP | isi-gl | ISI Graphics Language. |
| 56 | TCP/UDP | xns-auth | XNS Authentication. |
| 57 | TCP/UDP | — | Any Private Terminal Access. |
| 58 | TCP/UDP | xns-mail | XNS Mail. |
| 59 | TCP/UDP | — | Any Private File Service. |
| 60 | TCP/UDP | Unassigned | Non attribué dans le registre IANA. |
| 61 | TCP/UDP | Reserved | Entrée historique retirée du registre. |
| 62 | TCP/UDP | acas | ACA Services. |
| 63 | TCP/UDP | whoispp | WHOIS++ (historique). |
| 64 | TCP/UDP | covia | Communications Integrator (CI). |
| 65 | TCP/UDP | tacacs-ds | TACACS-Database Service. |
| 66 | TCP/UDP | sql-net | Oracle SQL*NET. |
| 67 | TCP/UDP | bootps | Bootstrap Protocol Server — BOOTP/DHCP serveur. |
| 68 | TCP/UDP | bootpc | Bootstrap Protocol Client — BOOTP/DHCP client. |
| 69 | TCP/UDP | tftp | Trivial File Transfer Protocol. |
| 70 | TCP/UDP | gopher | Gopher : protocole de distribution de documents. |
| 71 | TCP/UDP | netrjs-1 | Remote Job Service. |
| 72 | TCP/UDP | netrjs-2 | Remote Job Service. |
| 73 | TCP/UDP | netrjs-3 | Remote Job Service. |
| 74 | TCP/UDP | netrjs-4 | Remote Job Service. |
| 75 | TCP/UDP | — | Any Private Dial Out Service. |
| 76 | TCP/UDP | deos | Distributed External Object Store. |
| 77 | TCP/UDP | — | Any Private RJE Service. |
| 78 | TCP/UDP | vettcp | VETTCP. |
| 79 | TCP/UDP | finger | Finger : informations sur les utilisateurs d'un système. |
| 80 | TCP/UDP/SCTP | http | HTTP : Hypertext Transfer Protocol. |
| 81 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 82 | TCP/UDP | xfer | XFER Utility. |
| 83 | TCP/UDP | mit-ml-dev | MIT ML Device. |
| 84 | TCP/UDP | ctf | Common Trace Facility. |
| 85 | TCP/UDP | mit-ml-dev | MIT ML Device. |
| 86 | TCP/UDP | mfcobol | Micro Focus COBOL. |
| 87 | TCP | Unassigned | Non attribué dans le registre IANA. |
| 88 | TCP/UDP | kerberos | Kerberos : authentification réseau. |
| 89 | TCP/UDP | su-mit-tg | SU/MIT Telnet Gateway. |
| 90 | TCP/UDP | dnsix | DNSIX Security Attribute Token Map. |
| 91 | TCP/UDP | mit-dov | MIT Dover Spooler. |
| 92 | TCP/UDP | npp | Network Printing Protocol. |
| 93 | TCP/UDP | dcp | Device Control Protocol. |
| 94 | TCP/UDP | objcall | Tivoli Object Dispatcher. |
| 95 | TCP/UDP | supdup | SUPDUP Protocol. |
| 96 | TCP/UDP | dixie | DIXIE Protocol Specification. |
| 97 | TCP/UDP | swift-rvf | Swift Remote Virtual File Protocol. |
| 98 | TCP/UDP | tacnews | TAC News. |
| 99 | TCP/UDP | metagram | Metagram Relay. |
| 100 | TCP/UDP | newacct | New Account : service historique de création de compte. |
| 101 | TCP/UDP | hostname | NIC Host Name Server. |
| 102 | TCP/UDP | iso-tsap | ISO-TSAP Class 0. |
| 103 | TCP/UDP | gppitnp | Genesis Point-to-Point Trans Net. |
| 104 | TCP/UDP | acr-nema | ACR-NEMA Digital Imaging and Communications. |
| 105 | TCP/UDP | cso / csnet-ns | CCSO Nameserver / CSNET Mailbox Nameserver. |
| 106 | TCP/UDP | pop3pw | POP3 Password Change Service. |
| 107 | TCP/UDP | rtelnet | Remote Telnet Service. |
| 108 | TCP/UDP | snet | SNA Gateway Access Service. |
| 109 | TCP/UDP | pop2 | Post Office Protocol v2. |
| 110 | TCP/UDP | pop3 | Post Office Protocol v3. |
| 111 | TCP/UDP | sunrpc / rpcbind | Remote Procedure Call / Portmapper. |
| 112 | TCP/UDP | mcidas | McIDAS Data Transmission Protocol. |
| 113 | TCP/UDP | ident | Identification Protocol. |
| 114 | TCP | Unassigned | Statut IANA à vérifier. |
| 115 | TCP/UDP | sftp | Simple File Transfer Protocol (historique). |
| 116 | TCP/UDP | ansanotify | ANSA REX Notify. |
| 117 | TCP/UDP | uucp-path | UUCP Path Service. |
| 118 | TCP/UDP | sqlserv | SQL Services. |
| 119 | TCP/UDP | nntp | Network News Transfer Protocol. |
| 120 | TCP/UDP | cfdptkt | CFDPTKT. |
| 121 | TCP/UDP | erpc | Encore Remote Process Call. |
| 122 | TCP/UDP | smak | SMAK. |
| 123 | TCP/UDP | ntp | Network Time Protocol. |
| 124 | TCP/UDP | ansatrader | ANSA REX Trader. |
| 125 | TCP/UDP | locus-map | Locus PC-Interface Net Map Server. |
| 126 | TCP/UDP | nxedit | NXEdit (anciennement Unisys Unitary Login). |
| 127 | TCP/UDP | locus-con | Locus PC-Interface Conn Server. |
| 128 | TCP/UDP | gss-xlicen | GSS X License Verification. |
| 129 | TCP/UDP | pwdgen | Password Generator Protocol. |
| 130 | TCP/UDP | cisco-fna | Cisco FNATIVE. |
| 131 | TCP/UDP | cisco-tna | Cisco TNATIVE. |
| 132 | TCP/UDP | cisco-sys | Cisco SYSMAINT. |
| 133 | TCP/UDP | statsrv | Statistics Service. |
| 134 | TCP/UDP | ingres-net | INGRES-NET Service. |
| 135 | TCP/UDP | epmap | Microsoft Endpoint Mapper / DCE-RPC. |
| 136 | TCP/UDP | profile | PROFILE Naming System. |
| 137 | TCP/UDP | netbios-ns | NetBIOS Name Service. |
| 138 | TCP/UDP | netbios-dgm | NetBIOS Datagram Service. |
| 139 | TCP/UDP | netbios-ssn | NetBIOS Session Service. |
| 140 | TCP/UDP | emfis-data | EMFIS Data Service. |
| 141 | TCP/UDP | emfis-cntl | EMFIS Control Service. |
| 142 | TCP/UDP | bl-idm | Britton-Lee IDM. |
| 143 | TCP/UDP | imap | Internet Message Access Protocol. |
| 144 | TCP/UDP | uma | Universal Management Architecture. |
| 145 | TCP/UDP | uaac | UAAC Protocol. |
| 146 | TCP/UDP | iso-tp0 | ISO-IP0. |
| 147 | TCP/UDP | iso-ip | ISO-IP. |
| 148 | TCP/UDP | jargon | Jargon. |
| 149 | TCP/UDP | aed-512 | AED 512 Emulation Service. |
| 150 | TCP/UDP | sql-net | SQL-NET. |
| 151 | TCP/UDP | hems | HEMS. |
| 152 | TCP/UDP | bftp | Background File Transfer Protocol. |
| 153 | TCP/UDP | sgmp | Simple Gateway Monitoring Protocol. |
| 154 | TCP/UDP | netsc-dev | NETSC. |
| 155 | TCP/UDP | netsc | NETSC. |
| 156 | TCP/UDP | sql-net | SQL*NET. |
| 157 | TCP/UDP | knet-cmp | KNET/COMP. |
| 158 | TCP/UDP | pcmail-srv | PCMail Server. |
| 159 | TCP/UDP | nss-routing | NSS Routing. |
| 160 | TCP/UDP | sgmp-traps | SGMP Traps. |
| 161 | TCP/UDP | snmp | Simple Network Management Protocol. |
| 162 | TCP/UDP | snmptrap | SNMP Trap. |
| 163 | TCP/UDP | cmip-man | CMIP Management. |
| 164 | TCP/UDP | cmip-agent | CMIP Agent. |
| 165 | TCP/UDP | xns-courier | Xerox (XNS Courier). |
| 166 | TCP/UDP | s-net | Sirius Systems. |
| 167 | TCP/UDP | nntp | Network News Transfer Protocol (ancienne attribution). |
| 168 | TCP/UDP | rsvd | Reserved. |
| 169 | TCP/UDP | send | SEND. |
| 170 | TCP/UDP | print-srv | Network Printing Service. |
| 171 | TCP/UDP | multiplex | Multiplexing Protocol. |
| 172 | TCP/UDP | cl/1 | Network Services. |
| 173 | TCP/UDP | xyplex-mux | Xyplex Multiplexer. |
| 174 | TCP/UDP | mailq | Mail Queue Service. |
| 175 | TCP/UDP | vmnet | VMNET. |
| 176 | TCP/UDP | genrad | GENRAD. |
| 177 | TCP/UDP | xdmcp | X Display Manager Control Protocol. |
| 178 | TCP/UDP | nextstep | NextStep Window Server. |
| 179 | TCP/UDP | bgp | Border Gateway Protocol. |
| 180 | TCP/UDP | ris | Intergraph (RIS). |
| 181 | TCP/UDP | unify | Unify. |
| 182 | TCP/UDP | audit | Unisys Audit SITP. |
| 183 | TCP/UDP | ocbinder | OCBinder. |
| 184 | TCP/UDP | ocserver | OCServer. |
| 185 | TCP/UDP | remote-kis | Remote-KIS. |
| 186 | TCP/UDP | kis | KIS Protocol. |
| 187 | TCP/UDP | aci | Application Communication Interface. |
| 188 | TCP/UDP | mumps | Plus Five's MUMPS. |
| 189 | TCP/UDP | qft | Queued File Transport. |
| 190 | TCP/UDP | gacp | Gateway Access Control Protocol. |
| 191 | TCP/UDP | prospero | Prospero Directory Service. |
| 192 | TCP/UDP | osu-nms | OSU Network Monitoring System. |
| 193 | TCP/UDP | srmp | Spider Remote Monitoring Protocol. |
| 194 | TCP/UDP | irc | Internet Relay Chat. |
| 195 | TCP/UDP | dnsix | DNSIX Network Level Security. |
| 196 | TCP/UDP | dn6-nlm-aud | DNSIX Session Mgt Module Audit Redir. |
| 197 | TCP/UDP | dls | Directory Location Service. |
| 198 | TCP/UDP | dls-mon | Directory Location Service Monitor. |
| 199 | TCP/UDP | smux | SNMP Multiplexing Protocol. |
| 200 | TCP/UDP | src | IBM System Resource Controller. |
| 201 | TCP/UDP | at-rtmp | AppleTalk Routing Maintenance Protocol. |
| 202 | TCP/UDP | at-nbp | AppleTalk Name Binding Protocol. |
| 203 | TCP/UDP | at-3 | AppleTalk service historique. |
| 204 | TCP/UDP | at-echo | AppleTalk Echo. |
| 205 | TCP/UDP | at-5 | AppleTalk service historique. |
| 206 | TCP/UDP | at-zis | AppleTalk Zone Information Service. |
| 207 | TCP/UDP | at-7 | AppleTalk service historique. |
| 208 | TCP/UDP | at-8 | AppleTalk service historique. |
| 209 | TCP/UDP | qmtp | Quick Mail Transfer Protocol. |
| 210 | TCP/UDP | z39.50 | ANSI Z39.50 Information Retrieval. |
| 211 | TCP/UDP | 914c/g | Texas Instruments 914C/G. |
| 212 | TCP/UDP | anet | ANET. |
| 213 | TCP/UDP | ipx | IPX. |
| 214 | TCP/UDP | vmpwscs | VM PWSCS. |
| 215 | TCP/UDP | softpc | Insignia Solutions (SoftPC). |
| 216 | TCP/UDP | CAIlic | Computer Associates Int'l License Server. |
| 217 | TCP/UDP | dbase | dBASE Unix. |
| 218 | TCP/UDP | mpp | Netix Message Posting Protocol. |
| 219 | TCP/UDP | uarps | Unisys ARPs. |
| 220 | TCP/UDP | imap3 | IMAP Version 3 (ancienne attribution). |
| 221 | TCP/UDP | fln-spx | Berkeley rlogind with SPX auth. |
| 222 | TCP/UDP | rsh-spx | Berkeley rshd with SPX auth. |
| 223 | TCP/UDP | cdc | Certificate Distribution Center. |
| 224 | TCP/UDP | masqdialer | Masqdialer. |
| 225 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 226 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 227 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 228 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 229 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 230 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 231 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 232 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 233 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 234 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 235 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 236 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 237 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 238 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 239 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 240 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 241 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 242 | TCP/UDP | direct | Direct. |
| 243 | TCP/UDP | sur-meas | Survey Measurement. |
| 244 | TCP/UDP | inbusiness | Inbusiness. |
| 245 | TCP/UDP | link | LINK. |
| 246 | TCP/UDP | dsp3270 | Display Systems Protocol. |
| 247 | TCP/UDP | subntbcst_tftp | SUBNTBCST_TFTP. |
| 248 | TCP/UDP | bhfhs | BHFHS. |
| 249 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 250 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 251 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 252 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 253 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 254 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 255 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 256 | TCP/UDP | rap | RAP. |
| 257 | TCP/UDP | set | Secure Electronic Transaction. |
| 258 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 259 | TCP/UDP | esro-gen | Efficient Short Remote Operations. |
| 260 | TCP/UDP | openport | Openport. |
| 261 | TCP/UDP | nsiiops | IIOP Name Service over TLS/SSL. |
| 262 | TCP/UDP | arcisdms | Arcisdms. |
| 263 | TCP/UDP | hdap | HDAP. |
| 264 | TCP/UDP | bgmp | Border Gateway Multicast Protocol. |
| 265 | TCP/UDP | x-bone-ctl | X-Bone CTL. |
| 266 | TCP/UDP | sst | SCSI on ST. |
| 267 | TCP/UDP | td-service | Tobit David Service Layer. |
| 268 | TCP/UDP | td-replica | Tobit David Replica. |
| 269 | TCP/UDP | manet | MANET Protocols (RFC 5498). |
| 270 | TCP/UDP | gist | Q-mode encapsulation for GIST messages (UDP) / réservé (TCP). |
| 271 | TCP | pt-tls | IETF NEA Posture Transport Protocol over TLS. |
| 272 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 273 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 274 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 275 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 276 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 277 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 278 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 279 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 280 | TCP/UDP | http-mgmt | http-mgmt. |
| 281 | TCP/UDP | personal-link | Personal Link. |
| 282 | TCP/UDP | cableport-ax | Cable Port A/X. |
| 283 | TCP/UDP | rescap | rescap. |
| 284 | TCP/UDP | corerjd | corerjd. |
| 285 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 286 | TCP/UDP | fxp | FXP Communication. |
| 287 | TCP/UDP | k-block | K-BLOCK. |
| 288 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 289 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 290 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 291 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 292 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 293 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 294 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 295 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 296 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 297 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 298 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 299 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 300 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
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


## Inventaire des plages manquantes (liste de travail)

> Liste des numéros absents de la version précédente, fournie pour compléter l'inventaire. Les plages ci-dessous ne signifient pas que chaque port est officiellement « non attribué » : chaque numéro doit être vérifié au registre IANA avant de lui donner un nom ou un statut. Cette section sert de suivi de couverture, pas de registre officiel d'attributions.

### Ports système / Well-Known (0–1023)

Numéros signalés manquants :

`301–388, 390–426, 428–442, 444, 446–463, 466–499, 501, 504–513, 516–519, 522–523, 525–529, 531–542, 545–547, 549–553, 555–559, 561–562, 564–586, 588–592, 594–599, 601–622, 624–630, 632–635, 637–638, 640–645, 649–650, 652, 655–656, 658–659, 661–665, 667–673, 675–690, 693–699, 703–705, 707–710, 712–719, 721–748, 752, 755–759, 761–764, 766, 768–771, 773, 775–776, 778–782, 784–799, 802–807, 809–842, 844–872, 874–879, 881–887, 889–901, 904–907, 909–910, 913–988, 991, 996–999, 1001–1022`

### Ports enregistrés (1024–49151)

#### 1024–4999

`1031–1032, 1034–1039, 1045–1049, 1051–1052, 1055–1057, 1059, 1061–1065, 1067–1079, 1081–1089, 1091–1097, 1101–1108, 1112–1119, 1121–1122, 1124–1157, 1159–1193, 1196–1213, 1215–1233, 1235–1240, 1242–1269, 1271–1310, 1312–1336, 1338–1351, 1353–1413, 1415–1432, 1435–1493, 1495–1499, 1501–1520, 1523, 1526–1532, 1534–1582, 1584–1603, 1605–1644, 1647–1700, 1702–1719, 1721–1722, 1724–1754, 1756–1760, 1762–1800, 1802–1811, 1814–1862, 1864–1882, 1884–1899, 1901–1934, 1936–1961, 1963–1971, 1973–1983, 1985–1997, 1999, 2006–2007, 2009, 2011–2019, 2023–2029, 2031–2048, 2051–2081, 2084–2085, 2088–2094, 2097–2099, 2105–2120, 2122–2143, 2145–2151, 2153–2180, 2182–2199, 2201–2221, 2224–2250, 2252–2300, 2302–2322, 2324–2374, 2378, 2381–2398, 2400, 2402–2403, 2405–2426, 2428–2442, 2444–2482, 2485–2499, 2501–2524, 2526–2545, 2547–2597, 2599–2600, 2602–2603, 2605–2637, 2639–2699, 2711–2716, 2718–2799, 2801–2808, 2810, 2812–2868, 2870–2874, 2876–2999, 3011–3029, 3031–3049, 3051–3073, 3075–3127, 3131–3259, 3261–3267, 3270–3299, 3301–3305, 3308–3309, 3311–3332, 3334–3388, 3391–3399, 3401–3477, 3480–3499, 3501–3543, 3545–3631, 3633–3689, 3691–3701, 3703–3723, 3725–3783, 3786–3799, 3801–3999, 4002–4039, 4041–4059, 4061–4079, 4081–4099, 4101–4110, 4112–4124, 4126–4199, 4201–4221, 4223–4241, 4243–4299, 4301–4320, 4322–4442, 4446–4499, 4501–4566, 4568–4661, 4663–4671, 4673–4710, 4712–4788, 4790–4847, 4849–4898, 4900–4999`

#### 5000–9999

`5008–5009, 5011–5059, 5062–5089, 5091–5099, 5101–5139, 5141–5149, 5151–5199, 5202–5221, 5224–5268, 5270–5279, 5281–5297, 5299–5352, 5354, 5356–5431, 5434–5499, 5501–5553, 5556–5600, 5602–5630, 5633–5665, 5667–5670, 5673–5682, 5685–5699, 5701–5799, 5801–5899, 5904–5983, 5987–5999, 6011–6059, 6062–6378, 6380–6442, 6444–6499, 6501–6513, 6515–6542, 6544–6659, 6670–6678, 6680–6696, 6698–6880, 6882–6968, 6970–6999, 7004–7069, 7071–7099, 7101–7198, 7201–7442, 7444–7473, 7475–7686, 7688–7776, 7778–7799, 7801–7999, 8011–8019, 8021–8029, 8031–8039, 8041, 8043–8079, 8101–8110, 8112–8122, 8124, 8126–8138, 8140–8160, 8162–8179, 8182–8199, 8201–8221, 8223–8242, 8244–8279, 8281, 8283–8290, 8292–8332, 8335–8382, 8384–8399, 8401–8442, 8445–8499, 8501–8529, 8532–8553, 8555–8599, 8601–8648, 8650–8685, 8687–8760, 8762–8879, 8884–8887, 8891–8899, 8901–8999, 9007–9008, 9010–9041, 9043–9049, 9052–9059, 9061–9079, 9081–9089, 9095–9099, 9104–9109, 9112–9159, 9161–9199, 9202–9299, 9301–9417, 9419–9442, 9445–9499, 9501–9529, 9531–9534, 9536–9599, 9601–9665, 9667–9875, 9877–9897, 9899, 9901–9989, 9991–9998`

#### 10000–49151

`10002–10049, 10052–10079, 10081–10099, 10101–10249, 10251–10254, 10256–10442, 10444–10499, 10501–11210, 11212–11370, 11372–11999, 12001–12344, 12346–12999, 13001–13305, 13307–14329, 14331–14999, 15001–15671, 15673–15999, 16001–16999, 17001–18079, 18081–18180, 18182–18999, 19001–19999, 20002–20442, 20444–20999, 21001–21999, 22001–22099, 22101–22221, 22223–22999, 23001–23699, 23701–23999, 24001–24999, 25001–25564, 25566–26999, 27001–27014, 27016, 27020–27999, 28001–28016, 28018–29999, 30002–30079, 30081–30442, 30444–30999, 31001–31999, 32001–32763, 32765–32999, 33001–33889, 33891–34999, 35001–36999, 37001–39999, 40001–40999, 41001–41999, 42001–42999, 43001–43999, 44001–44999, 45001–45999, 46001–46999, 47001–47999, 48001–49151`

### Ports dynamiques / privés (49152–65535)

Aucun numéro manquant signalé dans cette plage dans la liste fournie : la couverture précédente inclut `49152` et `49153–65535`.

