# Catalogue des ports réseau

> Ports TCP/UDP classés par numéro croissant. Le numéro de port ne garantit pas le service : un service peut être configuré sur un autre port et un port peut être réutilisé. Cette première version liste les ports connus, courants et importants, pas la totalité des enregistrements IANA ni les 65 536 numéros.
>
> Plages : **0–1023** ports système/well-known; **1024–49151** ports enregistrés; **49152–65535** ports dynamiques/éphémères (plage courante, variable selon OS).

| Port | Protocole | Nom / service | Utilité |
|---:|---|---|---|
|  2484 TCP | Oracle TCPS | Oracle sécurisé (port souvent utilisé). |
|  2869 TCP | UPnP | UPnP eventing HTTP | Découverte/contrôle UPnP. |
|  6660–6669 | TCP | IRC | Ports IRC historiques. |
|  11371 TCP | HKP | Serveur de clés OpenPGP | HTTP Keyserver Protocol (port historique). |
|  49153–65535 | TCP/UDP | Ports dynamiques/privés | Ports éphémères choisis pour connexions client et services temporaires; pas de service fixe. |

## Références

- [IANA Service Name and Transport Protocol Port Number Registry](https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml)
- [RFC 6335 — Service Name and Port Number Procedures](https://www.rfc-editor.org/rfc/rfc6335)
- [RFC 6056 — Recommendations for Transport Protocol Port Randomization](https://www.rfc-editor.org/rfc/rfc6056)


## Inventaire des plages manquantes (liste de travail)

> Liste des numéros absents de la version précédente, fournie pour compléter l'inventaire. Les plages ci-dessous ne signifient pas que chaque port est officiellement « non attribué » : chaque numéro doit être vérifié au registre IANA avant de lui donner un nom ou un statut. Cette section sert de suivi de couverture, pas de registre officiel d'attributions.

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
| 301 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 302 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 303 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 304 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 305 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 306 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 307 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 308 | TCP/UDP | novastorbakcup | Novastor Backup. |
| 309 | TCP/UDP | entrusttime | EntrustTime. |
| 310 | TCP/UDP | bhmds | bhmds. |
| 311 | TCP/UDP | asip-webadmin | AppleShare IP WebAdmin. |
| 312 | TCP/UDP | vslmp | VSLMP. |
| 313 | TCP/UDP | magenta-logic | Magenta Logic. |
| 314 | TCP/UDP | opalis-robot | Opalis Robot. |
| 315 | TCP/UDP | dpsi | DPSI. |
| 316 | TCP/UDP | decauth | decAuth. |
| 317 | TCP/UDP | zannet | Zannet. |
| 318 | TCP/UDP | pkix-timestamp | PKIX TimeStamp. |
| 319 | TCP/UDP | ptp-event | PTP Event (Precision Time Protocol). |
| 320 | TCP/UDP | ptp-general | PTP General (Precision Time Protocol). |
| 321 | TCP/UDP | pip | PIP. |
| 322 | TCP/UDP | rtsps | RTSPS (RTSP sur TLS/SSL). |
| 323 | TCP | rpki-rtr | Resource PKI to Router Protocol (UDP réservé). |
| 324 | TCP | rpki-rtr-tls | Resource PKI to Router Protocol over TLS (UDP réservé). |
| 325 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 326 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 327 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 328 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 329 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 330 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 331 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 332 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 333 | TCP/UDP | texar | Texar Security Port. |
| 334 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 335 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 336 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 337 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 338 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 339 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 340 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 341 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 342 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 343 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 344 | TCP/UDP | pdap | Prospero Data Access Protocol. |
| 345 | TCP/UDP | pawserv | Perf Analysis Workbench. |
| 346 | TCP/UDP | zserv | Zebra server. |
| 347 | TCP/UDP | fatserv | Fatmen Server. |
| 348 | TCP/UDP | csi-sgwp | Cabletron Management Protocol. |
| 349 | TCP/UDP | mftp | mftp. |
| 350 | TCP/UDP | matip-type-a | MATIP Type A. |
| 351 | TCP/UDP | matip-type-b | MATIP Type B / bhoetty. |
| 352 | TCP/UDP | dtag-ste-sb | DTAG / bhoedap4. |
| 353 | TCP/UDP | ndsauth | NDSAUTH. |
| 354 | TCP/UDP | bh611 | bh611. |
| 355 | TCP/UDP | datex-asn | DATEX-ASN. |
| 356 | TCP/UDP | cloanto-net-1 | Cloanto Net 1 (Amiga Explorer). |
| 357 | TCP/UDP | bhevent | bhevent. |
| 358 | TCP/UDP | shrinkwrap | Shrinkwrap. |
| 359 | TCP/UDP | nsrmp | Network Security Risk Management Protocol. |
| 360 | TCP/UDP | scoi2odialog | scoi2odialog. |
| 361 | TCP/UDP | semantix | Semantix. |
| 362 | TCP/UDP | srssend | SRS Send. |
| 363 | TCP/UDP | rsvp-tunnel | RSVP Tunnel. |
| 364 | TCP/UDP | aurora-cmgr | Aurora CMGR. |
| 365 | TCP/UDP | dtk | DTK (Deception Tool Kit). |
| 366 | TCP/UDP | odmr | ODMR (On-Demand Mail Relay). |
| 367 | TCP/UDP | mortgageware | MortgageWare. |
| 368 | TCP/UDP | qbikgdp | QbikGDP. |
| 369 | TCP/UDP | rpc2portmap | rpc2portmap. |
| 370 | TCP/UDP | codaauth2 | codaauth2 (Coda authentication server). |
| 371 | TCP/UDP | clearcase | Clearcase. |
| 372 | TCP/UDP | ulistserv | ListProcessor (Unix Listserv). |
| 373 | TCP/UDP | legent-1 | Legent Corporation. |
| 374 | TCP/UDP | legent-2 | Legent Corporation. |
| 375 | TCP/UDP | hassle | Hassle. |
| 376 | TCP/UDP | nip | Amiga Envoy Network Inquiry Protocol. |
| 377 | TCP/UDP | tnETOS | NEC Corporation. |
| 378 | TCP/UDP | dsETOS | NEC Corporation. |
| 379 | TCP/UDP | is99c | TIA/EIA/IS-99 modem client. |
| 380 | TCP/UDP | is99s | TIA/EIA/IS-99 modem server. |
| 381 | TCP/UDP | hp-collector | HP performance data collector. |
| 382 | TCP/UDP | hp-managed-node | HP performance data managed node. |
| 383 | TCP/UDP | hp-alarm-mgr | HP performance data alarm manager. |
| 384 | TCP/UDP | arns | A Remote Network Server System. |
| 385 | TCP/UDP | ibm-app | IBM Application. |
| 386 | TCP/UDP | asa | ASA Message Router Object Def. |
| 387 | TCP/UDP | aurp | AppleTalk Update-Based Routing Protocol. |
| 388 | TCP/UDP | unidata-ldm | Unidata LDM. |
| 389 | TCP/UDP | LDAP | Annuaire LDAP. |
| 390 | TCP/UDP | uis | UIS. |
| 391 | TCP/UDP | synotics-relay | SynOptics SNMP Relay Port. |
| 392 | TCP/UDP | synotics-broker | SynOptics Port Broker Port. |
| 393 | TCP/UDP | meta5 | Meta5. |
| 394 | TCP/UDP | embl-ndt | EMBL Nucleic Data Transfer. |
| 395 | TCP/UDP | netcp | NetScout Control Protocol. |
| 396 | TCP/UDP | netware-ip | Novell Netware over IP. |
| 397 | TCP/UDP | mptn | Multi Protocol Trans. Net. |
| 398 | TCP/UDP | kryptolan | Kryptolan. |
| 399 | TCP/UDP | iso-tsap-c2 | ISO Transport Class 2 Non-Control over TCP. |
| 400 | TCP/UDP | ocbinder | Oracle Secure Backup (anciennement Work Solution). |
| 401 | TCP/UDP | ups | Uninterruptible Power Supply. |
| 402 | TCP/UDP | genie | Genie Protocol. |
| 403 | TCP/UDP | decap | decap. |
| 404 | TCP/UDP | nced | nced. |
| 405 | TCP/UDP | ncld | ncld. |
| 406 | TCP/UDP | imsp | Interactive Mail Support Protocol. |
| 407 | TCP/UDP | timbuktu | Timbuktu. |
| 408 | TCP/UDP | prm-sm | Prospero Resource Manager Sys. Man. |
| 409 | TCP/UDP | prm-nm | Prospero Resource Manager Node Man. |
| 410 | TCP/UDP | decladebug | DECLadebug Remote Debug Protocol. |
| 411 | TCP/UDP | rmt | Remote MT Protocol. |
| 412 | TCP/UDP | synoptics-trap | Trap Convention Port. |
| 413 | TCP/UDP | smsp | Storage Management Services Protocol. |
| 414 | TCP/UDP | infoseek | InfoSeek. |
| 415 | TCP/UDP | bnet | BNet. |
| 416 | TCP/UDP | silverplatter | Silverplatter. |
| 417 | TCP/UDP | onmux | Onmux. |
| 418 | TCP/UDP | hyper-g | Hyper-G. |
| 419 | TCP/UDP | ariel1 | Ariel 1. |
| 420 | TCP/UDP | smpte | SMPTE. |
| 421 | TCP/UDP | ariel2 | Ariel 2. |
| 422 | TCP/UDP | ariel3 | Ariel 3. |
| 423 | TCP/UDP | opc-job-start | IBM Operations Planning and Control Start. |
| 424 | TCP/UDP | opc-job-track | IBM Operations Planning and Control Track. |
| 425 | TCP/UDP | icad-el | ICAD. |
| 426 | TCP/UDP | smartsdp | smartsdp. |
| 427 | TCP/UDP | SLP | Service Location Protocol. |
| 428 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 429 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 430 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 431 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 432 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 433 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 434 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 435 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 436 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 437 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 438 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 439 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 440 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 441 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 442 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 443 | TCP | HTTPS | HTTP chiffré TLS. |
| 443 | UDP | QUIC/HTTP3 | HTTP/3 sur QUIC (UDP). |
| 444 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 445 | TCP | SMB | Partage fichiers/imprimantes Windows, SMB direct. |
| 446 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 447 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 448 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 449 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 450 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 451 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 452 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 453 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 454 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 455 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 456 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 457 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 458 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 459 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 460 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 461 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 462 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 463 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 464 | TCP/UDP | Kerberos password change | Changement de mot de passe Kerberos. |
| 465 | TCP | SMTPS | SMTP sur TLS implicite (usage courant). |
| 466 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 467 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 468 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 469 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 470 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 471 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 472 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 473 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 474 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 475 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 476 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 477 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 478 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 479 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 480 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 481 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 482 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 483 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 484 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 485 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 486 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 487 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 488 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 489 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 490 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 491 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 492 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 493 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 494 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 495 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 496 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 497 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 498 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 499 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 500 | UDP | IKE | Négociation IPsec. |
| 501 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 502 | TCP | Modbus | Protocole industriel Modbus TCP. |
| 503 | TCP | Intradomaine | Service historique/réservé; usage variable. |
| 504 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 505 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 506 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 507 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 508 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 509 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 510 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 511 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 512 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 513 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 514 | UDP | Syslog | Envoi de journaux (non chiffré traditionnel). |
| 515 | TCP | LPD/LPR | Impression réseau legacy. |
| 516 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 517 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 518 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 519 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 520 | UDP | RIP | Protocole de routage RIP. |
| 521 | UDP | RIPng | RIP pour IPv6. |
| 522 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 523 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 524 | TCP | NCP | NetWare Core Protocol. |
| 525 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 526 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 527 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 528 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 529 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  530 | TCP | RPC | Service RPC historique. |
| 531 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 532 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 533 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 534 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 535 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 536 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 537 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 538 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 539 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 540 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 541 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 542 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  543 | TCP | Klogin | Connexion distante Kerberos legacy. |
|  544 | TCP | Kshell | Shell distant Kerberos legacy. |
| 545 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 546 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 547 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  548 | TCP | AFP | Apple Filing Protocol. |
| 549 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 550 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 551 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 552 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 553 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  554 | TCP/UDP | RTSP | Contrôle de flux média. |
| 555 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 556 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 557 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 558 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 559 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  560 | UDP | RMON | Remote Monitoring legacy. |
| 561 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 562 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  563 | TCP | NNTPS | NNTP sur TLS. |
| 564 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 565 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 566 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 567 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 568 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 569 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 570 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 571 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 572 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 573 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 574 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 575 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 576 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 577 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 578 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 579 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 580 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 581 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 582 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 583 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 584 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 585 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 586 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  587 | TCP | SMTP Submission | Soumission de mail par clients, souvent STARTTLS. |
| 588 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 589 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 590 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 591 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 592 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  593 | TCP | RPC over HTTP | RPC sur HTTP (Windows). |
| 594 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 595 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 596 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 597 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 598 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 599 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  600 | TCP | IPC | Service IPC historique. |
| 601 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 602 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 603 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 604 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 605 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 606 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 607 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 608 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 609 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 610 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 611 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 612 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 613 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 614 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 615 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 616 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 617 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 618 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 619 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 620 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 621 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 622 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  623 | UDP | IPMI | Gestion hors bande des serveurs (BMC). |
| 624 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 625 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 626 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 627 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 628 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 629 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 630 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  631 | TCP/UDP | IPP | Impression Internet Protocol. |
| 632 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 633 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 634 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 635 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  636 | TCP | LDAPS | LDAP sur TLS. |
| 637 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 638 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  639 | TCP | MSRP | Multi-protocol Routing. |
| 640 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 641 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 642 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 643 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 644 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 645 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  646 | TCP | LDP | Label Distribution Protocol (MPLS). |
|  647 | TCP | DHCPv6 failover | Failover DHCP legacy. |
|  648 | TCP | RRP | Registry Remote Protocol. |
| 649 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 650 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  651 | TCP | Syslog TLS | Journaux via TLS (RFC 5425). |
| 652 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  653 | TCP/UDP | RRP | Service de routage historique. |
|  654 | TCP | AODV | Ad hoc On-Demand Distance Vector. |
| 655 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 656 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  657 | TCP | IBM RMC | Resource Monitoring and Control. |
| 658 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 659 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  660 | TCP | Apple Music / legacy | Port assigné historiquement à services Apple. |
| 661 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 662 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 663 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 664 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 665 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  666 | TCP | Doom | Port souvent associé à Doom; usage de jeu historique. |
| 667 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 668 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 669 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 670 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 671 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 672 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 673 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  674 | TCP | ACAP | Application Configuration Access Protocol. |
| 675 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 676 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 677 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 678 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 679 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 680 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 681 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 682 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 683 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 684 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 685 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 686 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 687 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 688 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 689 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 690 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  691 | TCP | Exchange Routing | Routage Exchange historique. |
|  692 | TCP | Hyperwave | Hyperwave server. |
| 693 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 694 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 695 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 696 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 697 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 698 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 699 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  700 | TCP | EPP | Extensible Provisioning Protocol. |
|  701 | TCP | LMP | Link Management Protocol. |
|  702 | TCP | IRIS | Service historique. |
| 703 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 704 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 705 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  706 | TCP | SILC | Secure Internet Live Conferencing. |
| 707 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 708 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 709 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 710 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  711 | TCP | TDP | Service historique. |
| 712 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 713 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 714 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 715 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 716 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 717 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 718 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 719 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  720 | TCP | NETVIEW | Service historique. |
| 721 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 722 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 723 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 724 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 725 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 726 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 727 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 728 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 729 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 730 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 731 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 732 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 733 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 734 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 735 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 736 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 737 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 738 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 739 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 740 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 741 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 742 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 743 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 744 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 745 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 746 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 747 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 748 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  749 | TCP/UDP | Kerberos Admin | Administration Kerberos. |
|  750 | UDP | Kerberos | Kerberos legacy. |
|  751 | TCP | Kerberos password | Service historique. |
| 752 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  753 | TCP | RRDP | Remote RWhois. |
|  754 | TCP | Tell | Service historique. |
| 755 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 756 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 757 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 758 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 759 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  760 | TCP | Kerberos | Service legacy. |
| 761 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 762 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 763 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 764 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  765 | TCP | Webster | Service historique. |
| 766 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  767 | TCP | Phone | Service historique. |
| 768 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 769 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 770 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 771 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  772 | TCP | COPS | Common Open Policy Service. |
| 773 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  774 | TCP | Rpasswd | Service historique. |
| 775 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 776 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  777 | TCP | Multiling HTTP | Port alternatif souvent utilisé par applications. |
| 778 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 779 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 780 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 781 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 782 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  783 | TCP | SpamAssassin | Filtrage anti-spam daemon. |
| 784 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 785 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 786 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 787 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 788 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 789 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 790 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 791 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 792 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 793 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 794 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 795 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 796 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 797 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 798 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 799 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  800 | TCP | HTTP alternate | Port web alternatif. |
|  801 | TCP | HTTP alternate | Port alternatif, usage applicatif. |
| 802 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 803 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 804 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 805 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 806 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 807 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  808 | TCP | HTTP alternate | Web alternatif fréquemment rencontré. |
| 809 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 810 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 811 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 812 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 813 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 814 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 815 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 816 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 817 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 818 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 819 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 820 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 821 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 822 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 823 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 824 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 825 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 826 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 827 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 828 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 829 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 830 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 831 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 832 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 833 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 834 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 835 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 836 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 837 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 838 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 839 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 840 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 841 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 842 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  843 | TCP | Flash policy | Ancien service de politique Flash. |
| 844 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 845 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 846 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 847 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 848 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 849 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 850 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 851 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 852 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 853 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 854 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 855 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 856 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 857 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 858 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 859 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 860 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 861 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 862 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 863 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 864 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 865 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 866 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 867 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 868 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 869 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 870 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 871 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 872 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  873 | TCP | rsync | Synchronisation de fichiers rsync daemon. |
| 874 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 875 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 876 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 877 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 878 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 879 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  880 | TCP | HTTP alternate | Port alternatif web. |
| 881 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 882 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 883 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 884 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 885 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 886 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 887 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  888 | TCP | HTTP alternate | Port web alternatif courant. |
| 889 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 890 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 891 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 892 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 893 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 894 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 895 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 896 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 897 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 898 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 899 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 900 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 901 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  902 | TCP/UDP | VMware | Console/communication VMware selon version. |
|  903 | TCP | VMware | Console VMware legacy. |
| 904 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 905 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 906 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 907 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  908 | TCP | HTTP alternate | Web alternatif. |
| 909 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 910 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  911 | TCP | HTTP alternate | Web alternatif. |
|  912 | TCP | VMware | Service VMware. |
| 913-988 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  989 | TCP | FTPS-data | Données FTP TLS implicite. |
|  990 | TCP | FTPS-control | Contrôle FTP TLS implicite. |
| 991 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  992 | TCP | Telnet TLS | Telnet sécurisé (legacy). |
|  993 | TCP | IMAPS | IMAP TLS implicite. |
|  994 | TCP | IRCS | IRC TLS (assignation historique). |
|  995 | TCP | POP3S | POP3 TLS implicite. |
| 996 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 997 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 998 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1000 | TCP | Web alternate | Port applicatif alternatif. |
| 1001 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1002 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1003 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1004 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1005 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1006 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1007 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1008 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1009 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1010 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1015 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1017 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1018 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1019 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1020 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1021 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1022 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1023 | TCP/UDP | Réserve fin ports système | Limite de plage well-known. |
|  1024 | TCP/UDP | Port système/privileged boundary | Début de la plage utilisateur/registered. |
|  1025 | TCP | Microsoft RPC | Port dynamique RPC fréquemment vu sur Windows ancien. |
|  1026 | TCP | Microsoft RPC | Port dynamique RPC fréquent. |
|  1027 | TCP | Microsoft RPC | Port dynamique RPC fréquent. |
|  1028 | TCP | Microsoft RPC | Port dynamique RPC fréquent. |
|  1029 | TCP | Microsoft RPC | Port dynamique RPC fréquent. |
|  1030 | TCP | Microsoft RPC | Port dynamique RPC fréquent. |
| 1031 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1032 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1033 | TCP | Netinfo | Service historique. |
| 1034 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1035 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1036 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1037 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1038 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1039 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1040 | TCP | Netscaler | Port applicatif selon configuration. |
|  1041 | TCP | Netscaler | Port applicatif selon configuration. |
|  1042 | TCP | Netscaler | Port applicatif selon configuration. |
|  1043 | TCP | Netscaler | Port applicatif selon configuration. |
|  1044 | TCP | Netscaler | Port applicatif selon configuration. |
| 1045 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1046 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1047 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1048 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1049 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1050 | TCP | Java RMI | RMI registry/communications selon configuration. |
| 1051 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1052 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1053 | TCP/UDP | DNS alternate | DNS alternatif. |
|  1054 | TCP | Adobe | Service historique. |
| 1055 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1056 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1057 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1058 | TCP | Nim | Service historique. |
| 1059 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1060 | TCP | PO | Service legacy. |
| 1061 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1062 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1063 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1064 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1065 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1066 | TCP | SQLNet | Service Oracle legacy. |
| 1067 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1068 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1069 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1070 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1071 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1072 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1073 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1074 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1075 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1076 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1077 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1078 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1079 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1080 | TCP | SOCKS proxy | Proxy SOCKS. |
| 1081 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1082 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1083 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1084 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1085 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1086 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1087 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1088 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1089 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1090 | TCP | SOCKS proxy alternate | Proxy alternatif. |
| 1091 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1092 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1093 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1094 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1095 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1096 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1097 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1098 | TCP | Java RMI | Service RMI. |
|  1099 | TCP | Java RMI Registry | Registre RMI Java. |
|  1100 | TCP | Java RMI | Port RMI courant dans certaines configurations. |
| 1101 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1102 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1103 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1104 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1105 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1106 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1107 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1108 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1109 | TCP | KPOP | POP Kerberos legacy. |
|  1110 | TCP | POP3 alternate | POP3 alternatif. |
|  1111 | TCP | Port applicatif | Port souvent choisi par applications de test. |
| 1112 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1113 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1114 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1115 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1116 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1117 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1118 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1119 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1120 | TCP | Port applicatif | Service spécifique selon configuration. |
| 1121 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1122 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1123 | TCP | MSSQL | Port alternatif SQL Server dans certains environnements. |
| 1124 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1125 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1126 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1127 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1128 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1129 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1130 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1131 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1132 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1133 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1134 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1135 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1136 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1137 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1138 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1139 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1140 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1141 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1142 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1143 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1144 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1145 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1146 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1147 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1148 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1149 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1150 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1151 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1152 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1153 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1154 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1155 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1156 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1157 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1158 | TCP | Oracle EM | Interface Oracle Enterprise Manager (ancienne). |
| 1159 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1160 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1161 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1162 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1163 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1164 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1165 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1166 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1167 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1168 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1169 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1170 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1171 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1172 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1173 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1174 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1175 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1176 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1177 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1178 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1179 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1180 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1181 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1182 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1183 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1184 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1185 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1186 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1187 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1188 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1189 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1190 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1191 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1192 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1193 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1194 | UDP/TCP | OpenVPN | VPN OpenVPN, port par défaut fréquent. |
|  1195 | UDP | OpenVPN alternate | Port alternatif. |
| 1196 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1197 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1198 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1199 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1200 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1201 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1202 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1203 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1204 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1205 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1206 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1207 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1208 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1209 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1210 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1211 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1212 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1213 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1214 | TCP | Kazaa | P2P historique. |
| 1215 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1216 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1217 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1218 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1219 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1220 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1221 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1222 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1223 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1224 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1225 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1226 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1227 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1228 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1229 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1230 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1231 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1232 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1233 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1234 | TCP/UDP | Port applicatif | Port fréquemment utilisé pour tests/services locaux. |
| 1235 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1236 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1237 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1238 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1239 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1240 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1241 | TCP | Nessus | Interface/communication Nessus historique. |
| 1242 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1243 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1244 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1245 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1246 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1247 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1248 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1249 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1250 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1251 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1252 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1253 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1254 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1255 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1256 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1257 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1258 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1259 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1260 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1261 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1262 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1263 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1264 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1265 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1266 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1267 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1268 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1269 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1270 | TCP | MOM | Microsoft Operations Manager legacy. |
| 1271 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1272 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1273 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1274 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1275 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1276 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1277 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1278 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1279 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1280 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1281 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1282 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1283 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1284 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1285 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1286 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1287 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1288 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1289 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1290 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1291 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1292 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1293 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1294 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1295 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1296 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1297 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1298 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1299 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1300 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1301 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1302 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1303 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1304 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1305 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1306 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1307 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1308 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1309 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1310 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1311 | TCP | Dell OpenManage | Administration serveur Dell. |
| 1312 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1313 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1314 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1315 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1316 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1317 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1318 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1319 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1320 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1321 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1322 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1323 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1324 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1325 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1326 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1327 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1328 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1329 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1330 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1331 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1332 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1333 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1334 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1335 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1336 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1337 | TCP | Leet / custom | Port non officiel populaire pour services personnalisés. |
| 1338 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1339 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1340 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1341 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1342 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1343 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1344 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1345 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1346 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1347 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1348 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1349 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1350 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1351 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1352 | TCP | Lotus Notes | Lotus Notes/Domino. |
| 1353-1413 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1414 | TCP | IBM MQ | Messaging IBM MQ. |
| 1415 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1416 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1417 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1418 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1419 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1420 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1421 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1422 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1423 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1424 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1425 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1426 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1427 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1428 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1429 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1430 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1431 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1432 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1433 | TCP | Microsoft SQL Server | Base de données SQL Server. |
|  1434 | UDP | SQL Server Browser | Découverte instances SQL Server. |
|  1434 | TCP | SQL Server | Port alternatif selon configuration. |
| 1435-1493 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1494 | TCP | Citrix ICA | Sessions Citrix. |
| 1495 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1496 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1497 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1498 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1499 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1500 | TCP | VLS | Service historique. |
| 1501 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1502 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1503 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1504 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1505 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1506 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1507 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1508 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1509 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1510 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1511 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1512 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1513 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1514 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1515 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1516 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1517 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1518 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1519 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1520 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1521 | TCP | Oracle Listener | Connexion Oracle DB. |
|  1522 | TCP | Oracle alternate | Port Oracle alternatif. |
| 1523 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1524 | TCP | ingreslock | Service legacy; parfois repéré dans anciens labs. |
|  1525 | TCP | Oracle alternate | Port alternatif Oracle. |
| 1526 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1527 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1528 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1529 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1530 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1531 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1532 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1533 | TCP | Sametime | IBM Sametime legacy. |
| 1534 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1535 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1536 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1537 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1538 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1539 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1540 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1541 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1542 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1543 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1544 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1545 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1546 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1547 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1548 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1549 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1550 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1551 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1552 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1553 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1554 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1555 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1556 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1557 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1558 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1559 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1560 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1561 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1562 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1563 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1564 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1565 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1566 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1567 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1568 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1569 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1570 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1571 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1572 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1573 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1574 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1575 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1576 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1577 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1578 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1579 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1580 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1581 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1582 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1583 | TCP | Pervasive SQL | Base Pervasive. |
| 1584 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1585 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1586 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1587 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1588 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1589 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1590 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1591 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1592 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1593 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1594 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1595 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1596 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1597 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1598 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1599 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1600 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1601 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1602 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1603 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1604 | TCP/UDP | Citrix | Service Citrix legacy. |
| 1605 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1606 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1607 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1608 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1609 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1610 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1611 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1612 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1613 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1614 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1615 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1616 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1617 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1618 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1619 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1620 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1621 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1622 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1623 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1624 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1625 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1626 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1627 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1628 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1629 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1630 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1631 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1632 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1633 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1634 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1635 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1636 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1637 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1638 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1639 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1640 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1641 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1642 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1643 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1644 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1645 | UDP | RADIUS auth (legacy) | Authentification RADIUS ancien port. |
|  1646 | UDP | RADIUS accounting (legacy) | Accounting RADIUS ancien port. |
| 1647-1700 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1701 | UDP | L2TP | Tunnel L2TP. |
| 1702 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1703 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1704 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1705 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1706 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1707 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1708 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1709 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1710 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1711 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1712 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1713 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1714 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1715 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1716 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1717 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1718 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1719 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1720 | TCP | H.323 | Signalisation H.323. |
| 1721 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1722 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1723 | TCP | PPTP | VPN PPTP (obsolète, sécurité faible). |
| 1724 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1725 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1726 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1727 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1728 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1729 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1730 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1731 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1732 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1733 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1734 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1735 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1736 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1737 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1738 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1739 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1740 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1741 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1742 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1743 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1744 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1745 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1746 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1747 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1748 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1749 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1750 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1751 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1752 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1753 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1754 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1755 | TCP/UDP | MMS | Microsoft Media Services legacy. |
| 1756 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1757 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1758 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1759 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1760 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1761 | TCP | Oracle | Service Oracle legacy. |
| 1762 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1763 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1764 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1765 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1766 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1767 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1768 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1769 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1770 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1771 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1772 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1773 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1774 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1775 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1776 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1777 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1778 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1779 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1780 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1781 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1782 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1783 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1784 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1785 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1786 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1787 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1788 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1789 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1790 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1791 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1792 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1793 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1794 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1795 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1796 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1797 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1798 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1799 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1800 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1801 | TCP/UDP | MSMQ | Microsoft Message Queuing. |
| 1802 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1803 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1804 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1805 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1806 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1807 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1808 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1809 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1810 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1811 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1812 | UDP | RADIUS auth | Authentification RADIUS. |
|  1813 | UDP | RADIUS accounting | Comptabilisation RADIUS. |
| 1814 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1815 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1816 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1817 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1818 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1819 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1820 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1821 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1822 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1823 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1824 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1825 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1826 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1827 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1828 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1829 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1830 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1831 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1832 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1833 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1834 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1835 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1836 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1837 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1838 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1839 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1840 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1841 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1842 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1843 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1844 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1845 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1846 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1847 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1848 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1849 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1850 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1851 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1852 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1853 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1854 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1855 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1856 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1857 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1858 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1859 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1860 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1861 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1862 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1863 | TCP | MSN Messenger | Service messagerie legacy. |
| 1864 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1865 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1866 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1867 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1868 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1869 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1870 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1871 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1872 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1873 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1874 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1875 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1876 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1877 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1878 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1879 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1880 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1881 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1882 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1883 | TCP | MQTT | IoT messaging sans TLS. |
| 1884 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1885 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1886 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1887 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1888 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1889 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1890 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1891 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1892 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1893 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1894 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1895 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1896 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1897 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1898 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1899 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1900 | UDP | SSDP | Découverte UPnP. |
| 1901 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1902 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1903 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1904 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1905 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1906 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1907 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1908 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1909 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1910 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1911 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1912 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1913 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1914 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1915 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1916 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1917 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1918 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1919 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1920 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1921 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1922 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1923 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1924 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1925 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1926 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1927 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1928 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1929 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1930 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1931 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1932 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1933 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1934 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1935 | TCP | RTMP | Streaming/média (legacy). |
| 1936 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1937 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1938 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1939 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1940 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1941 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1942 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1943 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1944 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1945 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1946 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1947 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1948 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1949 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1950 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1951 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1952 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1953 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1954 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1955 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1956 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1957 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1958 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1959 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1960 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1961 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1962 | TCP | PTC | Service industriel/application. |
| 1963 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1964 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1965 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1966 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1967 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1968 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1969 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1970 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1971 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1972 | TCP | Caché | Base Caché/InterSystems. |
| 1973 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1974 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1975 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1976 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1977 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1978 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1979 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1980 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1981 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1982 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1983 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1984 | TCP | Big Brother | Supervision legacy. |
| 1985 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1986 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1987 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1988 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1989 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1990 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1991 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1992 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1993 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1994 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1995 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1996 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 1997 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  1998 | TCP | Cisco X.25 | Service historique. |
| 1999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2000 | TCP/UDP | Cisco SCCP | VoIP Cisco Skinny. |
|  2001 | TCP | DC | Port applicatif fréquemment utilisé. |
|  2002 | TCP | DC | Port applicatif fréquemment utilisé. |
|  2003 | TCP | Graphite | Graphite carbon/metrics. |
|  2004 | TCP | Graphite | Graphite receiver selon configuration. |
|  2005 | TCP | Cisco SCCP | VoIP Cisco. |
| 2006 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2007 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2008 | TCP | Port applicatif | Usage variable. |
| 2009 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2010 | TCP | Port applicatif | Usage variable. |
| 2011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2015 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2017 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2018 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2019 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2020 | TCP | FTP alternate | FTP alternatif. |
|  2021 | TCP | FTP alternate | FTP alternatif. |
|  2022 | TCP | SSH alternate | SSH sur port non standard. |
| 2023 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2024 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2025 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2026 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2027 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2028 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2029 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2030 | TCP | Port applicatif | Usage variable. |
| 2031 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2032 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2033 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2034 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2035 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2036 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2037 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2038 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2039 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2040 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2041 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2042 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2043 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2044 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2045 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2046 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2047 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2048 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2049 | TCP/UDP | NFS | Partage de fichiers NFS. |
|  2050 | TCP | Port applicatif | Usage variable. |
| 2051 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2052 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2053 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2054 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2055 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2056 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2057 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2058 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2059 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2060 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2061 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2062 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2063 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2064 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2065 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2066 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2067 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2068 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2069 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2070 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2071 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2072 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2073 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2074 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2075 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2076 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2077 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2078 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2079 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2080 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2081 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2082 | TCP | cPanel | Interface cPanel non TLS. |
|  2083 | TCP | cPanel SSL | Interface cPanel TLS. |
| 2084 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2085 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2086 | TCP | WHM | WebHost Manager non TLS. |
|  2087 | TCP | WHM SSL | WHM TLS. |
| 2088 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2089 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2090 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2091 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2092 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2093 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2094 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2095 | TCP | Webmail | Webmail non TLS. |
|  2096 | TCP | Webmail SSL | Webmail TLS. |
| 2097 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2098 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2099 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2100 | TCP | Oracle XDB | Oracle XML DB/FTP selon config. |
|  2101 | TCP | NFS alternate | Service alternatif. |
|  2102 | TCP | Zephyr | Zephyr notification. |
|  2103 | TCP | Zephyr | Zephyr server. |
|  2104 | TCP | Zephyr | Zephyr client. |
| 2105 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2106 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2107 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2108 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2109 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2110 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2111 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2112 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2113 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2114 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2115 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2116 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2117 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2118 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2119 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2120 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2121 | TCP | FTP alternate | FTP sur port alternatif. |
| 2122 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2123 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2124 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2125 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2126 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2127 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2128 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2129 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2130 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2131 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2132 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2133 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2134 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2135 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2136 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2137 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2138 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2139 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2140 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2141 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2142 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2143 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2144 | TCP | Port applicatif | Usage variable. |
| 2145 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2146 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2147 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2148 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2149 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2150 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2151 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2152 | UDP | GTP-U | Tunnel de données mobile. |
| 2153 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2154 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2155 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2156 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2157 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2158 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2159 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2160 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2161 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2162 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2163 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2164 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2165 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2166 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2167 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2168 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2169 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2170 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2171 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2172 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2173 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2174 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2175 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2176 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2177 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2178 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2179 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2180 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2181 | TCP | ZooKeeper | Coordination cluster Apache ZooKeeper. |
| 2182 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2183 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2184 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2185 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2186 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2187 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2188 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2189 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2190 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2191 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2192 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2193 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2194 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2195 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2196 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2197 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2198 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2199 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2200 | TCP | SSH alternate | Port SSH alternatif courant. |
| 2201 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2202 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2203 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2204 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2205 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2206 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2207 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2208 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2209 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2210 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2211 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2212 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2213 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2214 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2215 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2216 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2217 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2218 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2219 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2220 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2221 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2222 | TCP | SSH alternate | Port alternatif souvent choisi. |
|  2223 | TCP | Port applicatif | Usage variable. |
| 2224 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2225 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2226 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2227 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2228 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2229 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2230 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2231 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2232 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2233 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2234 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2235 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2236 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2237 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2238 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2239 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2240 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2241 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2242 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2243 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2244 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2245 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2246 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2247 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2248 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2249 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2250 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2251 | TCP | Cisco | Service historique. |
| 2252 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2253 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2254 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2255 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2256 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2257 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2258 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2259 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2260 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2261 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2262 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2263 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2264 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2265 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2266 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2267 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2268 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2269 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2270 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2271 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2272 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2273 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2274 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2275 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2276 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2277 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2278 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2279 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2280 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2281 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2282 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2283 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2284 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2285 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2286 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2287 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2288 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2289 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2290 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2291 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2292 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2293 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2294 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2295 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2296 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2297 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2298 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2299 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2300 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2301 | TCP | Compaq Insight | Administration serveur legacy. |
| 2302 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2303 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2304 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2305 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2306 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2307 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2308 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2309 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2310 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2311 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2312 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2313 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2314 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2315 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2316 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2317 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2318 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2319 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2320 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2321 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2322 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2323 | TCP | Telnet alternate | Telnet alternatif (non chiffré). |
| 2324-2374 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2375 | TCP | Docker API | API Docker non TLS (à ne pas exposer). |
|  2376 | TCP | Docker TLS | API Docker TLS. |
|  2377 | TCP | Docker Swarm | Gestion cluster Swarm. |
| 2378 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2379 | TCP | etcd client | API client etcd. |
|  2380 | TCP | etcd peer | Communication entre membres etcd. |
| 2381 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2382 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2383 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2384 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2385 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2386 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2387 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2388 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2389 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2390 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2391 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2392 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2393 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2394 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2395 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2396 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2397 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2398 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2399 | TCP | FileMaker | Service FileMaker. |
| 2400 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2401 | TCP | CVS | Concurrent Versions System. |
| 2402 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2403 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2404 | TCP | IEC-104 | Protocole industriel téléconduite. |
| 2405 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2406 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2407 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2408 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2409 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2410 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2411 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2412 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2413 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2414 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2415 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2416 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2417 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2418 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2419 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2420 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2421 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2422 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2423 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2424 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2425 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2426 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2427 | UDP | MGCP | Media Gateway Control. |
| 2428 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2429 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2430 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2431 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2432 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2433 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2434 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2435 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2436 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2437 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2438 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2439 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2440 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2441 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2442 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2443 | TCP | HTTPS alternate | Port TLS alternatif. |
| 2444 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2445 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2446 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2447 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2448 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2449 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2450 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2451 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2452 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2453 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2454 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2455 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2456 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2457 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2458 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2459 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2460 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2461 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2462 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2463 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2464 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2465 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2466 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2467 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2468 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2469 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2470 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2471 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2472 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2473 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2474 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2475 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2476 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2477 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2478 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2479 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2480 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2481 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2482 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2483 | TCP | Oracle TCPS | Oracle sur TLS. |
| 2484 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2485 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2486 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2487 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2488 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2489 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2490 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2491 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2492 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2493 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2494 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2495 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2496 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2497 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2498 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2499 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2500 | TCP | RPC | Port applicatif/RPC variable. |
| 2501 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2502 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2503 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2504 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2505 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2506 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2507 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2508 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2509 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2510 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2511 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2512 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2513 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2514 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2515 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2516 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2517 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2518 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2519 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2520 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2521 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2522 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2523 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2524 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2525 | TCP | SMTP alternate | Soumission SMTP alternative. |
| 2526 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2527 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2528 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2529 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2530 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2531 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2532 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2533 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2534 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2535 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2536 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2537 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2538 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2539 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2540 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2541 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2542 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2543 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2544 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2545 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2546 | TCP | Port applicatif | Usage variable. |
| 2547-2597 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2598 | TCP | Citrix | Citrix Session Reliability. |
| 2599 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2600 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2601 | TCP | Zebra | Routage Zebra legacy. |
| 2602 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2603 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2604 | TCP | BGPd | Gestion routeur/quagga legacy. |
| 2605 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2606 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2607 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2608 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2609 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2610 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2611 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2612 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2613 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2614 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2615 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2616 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2617 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2618 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2619 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2620 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2621 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2622 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2623 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2624 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2625 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2626 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2627 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2628 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2629 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2630 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2631 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2632 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2633 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2634 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2635 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2636 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2637 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2638 | TCP | SQL Anywhere | Base SQL Anywhere. |
| 2639-2699 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
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
| 2711 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2712 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2713 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2714 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2715 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2716 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2717 | TCP | PNMS | Service legacy. |
| 2718-2799 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2800 | TCP | HTTP alternate | Port web alternatif. |
| 2801 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2802 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2803 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2804 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2805 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2806 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2807 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 2808 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2809 | TCP | CORBA | Naming service CORBA. |
| 2810 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2811 | TCP | GSI FTP | GridFTP service. |
| 2812-2874 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  2875 | TCP | Port applicatif | Usage variable. |
| 2876-2999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
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
| 3011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3015 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3017 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3018 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3019 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3020 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3021 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3022 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3023 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3024 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3025 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3026 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3027 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3028 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3029 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3030 | TCP | Web alternate | Web alternatif. |
| 3031 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3032 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3033 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3034 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3035 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3036 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3037 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3038 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3039 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3040 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3041 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3042 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3043 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3044 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3045 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3046 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3047 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3048 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3049 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3050 | TCP | Firebird | Base Firebird. |
| 3051 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3052 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3053 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3054 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3055 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3056 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3057 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3058 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3059 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3060 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3061 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3062 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3063 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3064 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3065 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3066 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3067 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3068 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3069 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3070 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3071 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3072 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3073 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3074 | TCP/UDP | Xbox Live | Jeux/communications Xbox. |
| 3075-3127 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3128 | TCP | Squid proxy | Proxy HTTP Squid fréquent. |
|  3129 | TCP | Proxy alternate | Proxy alternatif. |
|  3130 | TCP | ICP | Internet Cache Protocol. |
| 3131-3259 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3260 | TCP | iSCSI | Stockage réseau iSCSI. |
| 3261 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3262 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3263 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3264 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3265 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3266 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3267 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3268 | TCP | LDAP Global Catalog | Catalogue global Active Directory. |
|  3269 | TCP | LDAPS Global Catalog | Catalogue global AD sur TLS. |
| 3270 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3271 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3272 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3273 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3274 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3275 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3276 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3277 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3278 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3279 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3280 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3281 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3282 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3283 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3284 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3285 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3286 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3287 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3288 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3289 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3290 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3291 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3292 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3293 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3294 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3295 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3296 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3297 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3298 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3299 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3300 | TCP | Port applicatif | Usage variable. |
| 3301 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3302 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3303 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3304 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3305 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3306 | TCP | MySQL/MariaDB | Base de données MySQL/MariaDB. |
|  3307 | TCP | MySQL alternate | Port DB alternatif. |
| 3308 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3309 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3310 | TCP | ClamAV | ClamAV daemon (clamd). |
| 3311 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3312 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3313 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3314 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3315 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3316 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3317 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3318 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3319 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3320 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3321 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3322 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3323 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3324 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3325 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3326 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3327 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3328 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3329 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3330 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3331 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3332 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3333 | TCP | Port applicatif | Port souvent utilisé par services/tests. |
| 3334-3388 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3389 | TCP/UDP | RDP | Bureau distant Windows. |
|  3390 | TCP | RDP alternate | RDP port alternatif. |
| 3391 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3392 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3393 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3394 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3395 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3396 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3397 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3398 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3399 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3400 | TCP | Port applicatif | Usage variable. |
| 3401-3477 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3478 | TCP/UDP | STUN/TURN | Traversée NAT et média temps réel. |
|  3479 | TCP/UDP | TURN alternate | Services traversée NAT. |
| 3480 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3481 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3482 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3483 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3484 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3485 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3486 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3487 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3488 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3489 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3490 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3491 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3492 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3493 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3494 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3495 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3496 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3497 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3498 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3499 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3500 | TCP | Port applicatif | Usage variable. |
| 3501 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3502 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3503 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3504 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3505 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3506 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3507 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3508 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3509 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3510 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3511 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3512 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3513 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3514 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3515 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3516 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3517 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3518 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3519 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3520 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3521 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3522 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3523 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3524 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3525 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3526 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3527 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3528 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3529 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3530 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3531 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3532 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3533 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3534 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3535 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3536 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3537 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3538 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3539 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3540 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3541 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3542 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3543 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3544 | UDP | Teredo | Tunnel IPv6 Teredo. |
| 3545-3631 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3632 | TCP | distcc | Compilation distribuée. |
| 3633-3689 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3690 | TCP | SVN | Subversion version control. |
| 3691 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3692 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3693 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3694 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3695 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3696 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3697 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3698 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3699 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3700 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3701 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3702 | UDP | WS-Discovery | Découverte de services sur LAN. |
| 3703 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3704 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3705 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3706 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3707 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3708 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3709 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3710 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3711 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3712 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3713 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3714 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3715 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3716 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3717 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3718 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3719 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3720 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3721 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3722 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3723 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3724 | TCP | Blizzard | Jeux/launcher historique. |
| 3725-3783 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3784 | UDP | BFD | Détection rapide de défaillance de routage. |
|  3785 | UDP | BFD | BFD selon mode/config. |
| 3786 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3787 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3788 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3789 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3790 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3791 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3792 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3793 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3794 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3795 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3796 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3797 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3798 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 3799 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  3800 | TCP | Port applicatif | Usage variable. |
| 3801-3999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4000 | TCP | Web alternate | Port applicatif/web courant. |
|  4001 | TCP | Web alternate | Port alternatif. |
| 4002 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4003 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4004 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4005 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4006 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4007 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4008 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4009 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4010 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4015 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4017 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4018 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4019 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4020 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4021 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4022 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4023 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4024 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4025 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4026 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4027 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4028 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4029 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4030 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4031 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4032 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4033 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4034 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4035 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4036 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4037 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4038 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4039 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4040 | TCP | Spark | Interface Spark (souvent web). |
| 4041 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4042 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4043 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4044 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4045 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4046 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4047 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4048 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4049 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4050 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4051 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4052 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4053 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4054 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4055 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4056 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4057 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4058 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4059 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4060 | TCP | Port applicatif | Usage variable. |
| 4061 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4062 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4063 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4064 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4065 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4066 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4067 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4068 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4069 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4070 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4071 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4072 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4073 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4074 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4075 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4076 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4077 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4078 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4079 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4080 | TCP | Web alternate | Port web alternatif. |
| 4081 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4082 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4083 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4084 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4085 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4086 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4087 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4088 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4089 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4090 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4091 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4092 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4093 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4094 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4095 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4096 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4097 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4098 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4099 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4100 | TCP | Web alternate | Port web alternatif. |
| 4101 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4102 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4103 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4104 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4105 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4106 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4107 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4108 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4109 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4110 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4111 | TCP | Xgrid | Service Apple legacy. |
| 4112 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4113 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4114 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4115 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4116 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4117 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4118 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4119 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4120 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4121 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4122 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4123 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4124 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4125 | TCP | Port applicatif | Usage variable. |
| 4126-4199 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4200 | TCP | Web dev | Serveur de développement web fréquent. |
| 4201 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4202 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4203 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4204 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4205 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4206 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4207 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4208 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4209 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4210 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4211 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4212 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4213 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4214 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4215 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4216 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4217 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4218 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4219 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4220 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4221 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4222 | TCP | NATS | Messaging NATS. |
| 4223 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4224 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4225 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4226 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4227 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4228 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4229 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4230 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4231 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4232 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4233 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4234 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4235 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4236 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4237 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4238 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4239 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4240 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4241 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4242 | TCP | Port applicatif | Port populaire de service/test. |
| 4243-4299 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4300 | TCP | Web alternate | Port web alternatif. |
| 4301 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4302 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4303 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4304 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4305 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4306 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4307 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4308 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4309 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4310 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4311 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4312 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4313 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4314 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4315 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4316 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4317 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4318 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4319 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4320 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4321 | TCP | Rwhois | Service historique. |
| 4322-4442 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4443 | TCP | HTTPS alternate | HTTPS sur port alternatif. |
|  4444 | TCP | Port applicatif | Port souvent utilisé par outils/tests; service variable. |
|  4445 | TCP | Port applicatif | Usage variable. |
| 4446-4499 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4500 | UDP | IPsec NAT-T | Tunnel IPsec à travers NAT. |
| 4501-4566 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4567 | TCP | Port applicatif | Usage variable. |
| 4568-4661 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4662 | TCP | eDonkey | P2P legacy. |
| 4663 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4664 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4665 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4666 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4667 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4668 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4669 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4670 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4671 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4672 | UDP | eMule | P2P legacy. |
| 4673 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4674 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4675 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4676 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4677 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4678 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4679 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4680 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4681 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4682 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4683 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4684 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4685 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4686 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4687 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4688 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4689 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4690 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4691 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4692 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4693 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4694 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4695 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4696 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4697 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4698 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4699 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4700 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4701 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4702 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4703 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4704 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4705 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4706 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4707 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4708 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4709 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4710 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4711 | TCP | Port applicatif | Usage variable. |
| 4712-4788 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4789 | UDP | VXLAN | Overlay réseau VXLAN. |
| 4790-4847 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4848 | TCP | GlassFish | Administration GlassFish. |
| 4849 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4850 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4851 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4852 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4853 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4854 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4855 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4856 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4857 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4858 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4859 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4860 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4861 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4862 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4863 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4864 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4865 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4866 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4867 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4868 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4869 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4870 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4871 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4872 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4873 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4874 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4875 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4876 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4877 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4878 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4879 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4880 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4881 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4882 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4883 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4884 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4885 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4886 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4887 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4888 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4889 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4890 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4891 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4892 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4893 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4894 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4895 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4896 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4897 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 4898 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  4899 | TCP | Radmin | Administration distante Radmin. |
| 4900-4999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5000 | TCP | Flask/dev/web | Port web/dev fréquent; service dépendant. |
|  5001 | TCP | HTTPS alternate | Web/TLS alternatif; aussi iPerf selon configuration. |
|  5002 | TCP | Port applicatif | Usage variable. |
|  5003 | TCP | FileMaker | FileMaker service. |
|  5004 | UDP | RTP | Média RTP (configuration). |
|  5005 | UDP | RTCP | Contrôle média RTCP. |
|  5006 | TCP | Port applicatif | Usage variable. |
|  5007 | TCP | Port applicatif | Usage variable. |
| 5008 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5009 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5010 | TCP | Port applicatif | Usage variable. |
| 5011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5015 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5017 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5018 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5019 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5020 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5021 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5022 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5023 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5024 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5025 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5026 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5027 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5028 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5029 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5030 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5031 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5032 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5033 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5034 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5035 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5036 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5037 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5038 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5039 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5040 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5041 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5042 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5043 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5044 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5045 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5046 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5047 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5048 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5049 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5050 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5051 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5052 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5053 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5054 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5055 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5056 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5057 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5058 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5059 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5060 | TCP/UDP | SIP | Signalisation VoIP. |
|  5061 | TCP | SIP-TLS | Signalisation SIP chiffrée. |
| 5062 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5063 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5064 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5065 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5066 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5067 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5068 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5069 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5070 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5071 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5072 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5073 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5074 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5075 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5076 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5077 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5078 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5079 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5080 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5081 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5082 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5083 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5084 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5085 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5086 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5087 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5088 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5089 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5090 | TCP/UDP | SIP alternate | SIP alternatif. |
| 5091 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5092 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5093 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5094 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5095 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5096 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5097 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5098 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5099 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5100 | TCP | X11 alternate | X11 alternatif. |
| 5101 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5102 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5103 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5104 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5105 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5106 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5107 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5108 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5109 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5110 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5111 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5112 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5113 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5114 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5115 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5116 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5117 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5118 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5119 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5120 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5121 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5122 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5123 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5124 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5125 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5126 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5127 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5128 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5129 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5130 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5131 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5132 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5133 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5134 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5135 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5136 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5137 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5138 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5139 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5140 | TCP | Syslog alternate | Journaux alternatif. |
| 5141 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5142 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5143 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5144 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5145 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5146 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5147 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5148 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5149 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5150 | TCP | Port applicatif | Usage variable. |
| 5151 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5152 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5153 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5154 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5155 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5156 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5157 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5158 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5159 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5160 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5161 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5162 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5163 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5164 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5165 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5166 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5167 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5168 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5169 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5170 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5171 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5172 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5173 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5174 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5175 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5176 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5177 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5178 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5179 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5180 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5181 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5182 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5183 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5184 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5185 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5186 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5187 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5188 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5189 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5190 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5191 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5192 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5193 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5194 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5195 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5196 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5197 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5198 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5199 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5200 | TCP | Port applicatif | Usage variable. |
|  5201 | TCP/UDP | iperf3 | Mesure de débit réseau. |
| 5202 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5203 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5204 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5205 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5206 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5207 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5208 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5209 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5210 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5211 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5212 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5213 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5214 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5215 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5216 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5217 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5218 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5219 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5220 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5221 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5222 | TCP | XMPP client | Messagerie XMPP. |
|  5223 | TCP | XMPP TLS legacy | XMPP TLS historique. |
| 5224 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5225 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5226 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5227 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5228 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5229 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5230 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5231 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5232 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5233 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5234 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5235 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5236 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5237 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5238 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5239 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5240 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5241 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5242 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5243 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5244 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5245 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5246 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5247 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5248 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5249 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5250 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5251 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5252 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5253 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5254 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5255 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5256 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5257 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5258 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5259 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5260 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5261 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5262 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5263 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5264 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5265 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5266 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5267 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5268 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5269 | TCP | XMPP server | Connexions serveur XMPP. |
| 5270 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5271 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5272 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5273 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5274 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5275 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5276 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5277 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5278 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5279 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5280 | TCP | XMPP HTTP | Interface/HTTP XMPP. |
| 5281 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5282 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5283 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5284 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5285 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5286 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5287 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5288 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5289 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5290 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5291 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5292 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5293 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5294 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5295 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5296 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5297 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5298 | TCP | XMPP | Service XMPP legacy. |
| 5299-5352 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5353 | UDP | mDNS | Découverte multicast DNS locale. |
| 5354 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5355 | UDP | LLMNR | Résolution locale de noms. |
| 5356-5431 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5432 | TCP | PostgreSQL | Base de données PostgreSQL. |
|  5433 | TCP | PostgreSQL alternate | Port PostgreSQL alternatif. |
| 5434-5499 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5500 | TCP | VNC alternate | VNC/port applicatif selon config. |
| 5501-5553 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5554 | TCP | RTSP alternate | Port média/RTSP alternatif. |
|  5555 | TCP | Android Debug Bridge | ADB TCP (si activé). |
| 5556 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5557 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5558 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5559 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5560 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5561 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5562 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5563 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5564 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5565 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5566 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5567 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5568 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5569 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5570 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5571 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5572 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5573 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5574 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5575 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5576 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5577 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5578 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5579 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5580 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5581 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5582 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5583 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5584 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5585 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5586 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5587 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5588 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5589 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5590 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5591 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5592 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5593 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5594 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5595 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5596 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5597 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5598 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5599 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5600 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5601 | TCP | Kibana | Interface Kibana web. |
| 5602 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5603 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5604 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5605 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5606 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5607 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5608 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5609 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5610 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5611 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5612 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5613 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5614 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5615 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5616 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5617 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5618 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5619 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5620 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5621 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5622 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5623 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5624 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5625 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5626 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5627 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5628 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5629 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5630 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5631 | TCP | PCAnywhere | Remote access legacy. |
|  5632 | UDP | PCAnywhere | Remote access legacy. |
| 5633 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5634 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5635 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5636 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5637 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5638 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5639 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5640 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5641 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5642 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5643 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5644 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5645 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5646 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5647 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5648 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5649 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5650 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5651 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5652 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5653 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5654 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5655 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5656 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5657 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5658 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5659 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5660 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5661 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5662 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5663 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5664 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5665 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5666 | TCP | NRPE | Nagios Remote Plugin Executor. |
| 5667 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5668 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5669 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5670 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5671 | TCP | AMQP TLS | Messaging AMQP TLS. |
|  5672 | TCP | AMQP | Messaging RabbitMQ/AMQP. |
| 5673 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5674 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5675 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5676 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5677 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5678 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5679 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5680 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5681 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5682 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5683 | UDP | CoAP | IoT REST-like protocol. |
|  5684 | UDP | CoAP TLS/DTLS | CoAP sécurisé. |
| 5685 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5686 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5687 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5688 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5689 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5690 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5691 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5692 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5693 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5694 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5695 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5696 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5697 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5698 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5699 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5700 | TCP | VNC alternate | Port VNC alternatif. |
| 5701-5799 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5800 | TCP | VNC web | Interface web VNC (configuration). |
| 5801-5899 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5900 | TCP | VNC | Bureau distant VNC. |
|  5901 | TCP | VNC display 1 | VNC display/port additionnel. |
|  5902 | TCP | VNC display 2 | VNC display/port additionnel. |
|  5903 | TCP | VNC display 3 | VNC display/port additionnel. |
| 5904-5983 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  5984 | TCP | CouchDB | API CouchDB. |
|  5985 | TCP | WinRM HTTP | Administration Windows via HTTP. |
|  5986 | TCP | WinRM HTTPS | Administration Windows via HTTPS. |
| 5987 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5988 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5989 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5990 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5991 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5992 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5993 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5994 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5995 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5996 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5997 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5998 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 5999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
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
| 6011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6015 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6017 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6018 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6019 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6020 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6021 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6022 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6023 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6024 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6025 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6026 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6027 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6028 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6029 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6030 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6031 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6032 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6033 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6034 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6035 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6036 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6037 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6038 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6039 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6040 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6041 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6042 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6043 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6044 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6045 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6046 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6047 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6048 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6049 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6050 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6051 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6052 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6053 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6054 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6055 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6056 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6057 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6058 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6059 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  6060 | TCP | Web alternate | Port web/app alternatif. |
|  6061 | TCP | Web alternate | Port web/app alternatif. |
| 6062-6378 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  6379 | TCP | Redis | Cache/clé-valeur Redis. |
| 6380-6442 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  6443 | TCP | Kubernetes API | API Kubernetes souvent TLS. |
| 6444-6499 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  6500 | TCP | Port applicatif | Usage variable. |
| 6501 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6502 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6503 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6504 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6505 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6506 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6507 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6508 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6509 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6510 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6511 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6512 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6513 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  6514 | TCP | Syslog TLS | Syslog sécurisé TLS. |
| 6515 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6516 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6517 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6518 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6519 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6520 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6521 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6522 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6523 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6524 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6525 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6526 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6527 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6528 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6529 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6530 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6531 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6532 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6533 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6534 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6535 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6536 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6537 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6538 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6539 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6540 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6541 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6542 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  6543 | TCP | PostgreSQL alternate | Port DB alternatif. |
| 6544-6678 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  6679 | TCP | IRC alternate | IRC alternatif. |
| 6680 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6681 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6682 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6683 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6684 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6685 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6686 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6687 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6688 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6689 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6690 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6691 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6692 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6693 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6694 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6695 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6696 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  6697 | TCP | IRC TLS | IRC sécurisé. |
| 6698-6880 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  6881 | TCP/UDP | BitTorrent | P2P BitTorrent (port historique). |
| 6882-6968 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  6969 | TCP/UDP | BitTorrent tracker | Tracker BitTorrent fréquent. |
| 6970 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6971 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6972 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6973 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6974 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6975 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6976 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6977 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6978 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6979 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6980 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6981 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6982 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6983 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6984 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6985 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6986 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6987 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6988 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6989 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6990 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6991 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6992 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6993 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6994 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6995 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6996 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6997 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6998 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 6999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  7000 | TCP | Web alternate | Port web/app alternatif. |
|  7001 | TCP | WebLogic | WebLogic admin/application. |
|  7002 | TCP | WebLogic TLS | WebLogic sécurisé. |
|  7003 | TCP | Web alternate | Port web alternatif. |
| 7004-7069 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  7070 | TCP | RTSP/HTTP alternate | Média/HTTP selon service. |
| 7071 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7072 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7073 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7074 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7075 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7076 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7077 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7078 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7079 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7080 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7081 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7082 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7083 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7084 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7085 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7086 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7087 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7088 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7089 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7090 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7091 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7092 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7093 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7094 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7095 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7096 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7097 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7098 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7099 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  7100 | TCP | X font server | Service fonts X legacy. |
| 7101-7198 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  7199 | TCP | Cassandra JMX | Gestion Cassandra JMX (config). |
|  7200 | TCP | Port applicatif | Usage variable. |
| 7201-7442 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  7443 | TCP | HTTPS alternate | HTTPS alternatif. |
| 7444 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7445 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7446 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7447 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7448 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7449 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7450 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7451 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7452 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7453 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7454 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7455 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7456 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7457 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7458 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7459 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7460 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7461 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7462 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7463 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7464 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7465 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7466 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7467 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7468 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7469 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7470 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7471 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7472 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7473 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  7474 | TCP | Neo4j HTTP | Interface/API Neo4j. |
| 7475-7686 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  7687 | TCP | Neo4j Bolt | Protocole Bolt Neo4j. |
| 7688-7776 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  7777 | TCP | Port applicatif | Port fréquemment utilisé par applications. |
| 7778 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7779 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7780 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7781 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7782 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7783 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7784 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7785 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7786 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7787 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7788 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7789 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7790 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7791 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7792 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7793 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7794 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7795 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7796 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7797 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7798 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 7799 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  7800 | TCP | Port applicatif | Usage variable. |
| 7801-7999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
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
| 8011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8015 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8017 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8018 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8019 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8020 | TCP | Hadoop | Hadoop namenode/IPC selon config. |
| 8021 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8022 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8023 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8024 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8025 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8026 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8027 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8028 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8029 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8030 | TCP | Hadoop | Service Hadoop. |
| 8031 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8032 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8033 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8034 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8035 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8036 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8037 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8038 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8039 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8040 | TCP | Hadoop | Service Hadoop. |
| 8041 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8042 | TCP | Hadoop YARN | NodeManager web UI. |
| 8043 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8044 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8045 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8046 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8047 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8048 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8049 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8050 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8051 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8052 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8053 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8054 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8055 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8056 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8057 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8058 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8059 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8060 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8061 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8062 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8063 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8064 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8065 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8066 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8067 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8068 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8069 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8070 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8071 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8072 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8073 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8074 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8075 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8076 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8077 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8078 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8079 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
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
| 8101 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8102 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8103 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8104 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8105 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8106 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8107 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8108 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8109 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8110 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8111 | TCP | HTTP alternate | Web/app; JetBrains TeamCity par défaut. |
| 8112 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8113 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8114 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8115 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8116 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8117 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8118 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8119 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8120 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8121 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8122 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8123 | TCP | Home Assistant | Interface/API Home Assistant. |
| 8124 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8125 | UDP | StatsD | Collecte métriques StatsD. |
| 8126 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8127 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8128 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8129 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8130 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8131 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8132 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8133 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8134 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8135 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8136 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8137 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8138 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8139 | TCP | HTTP alternate | Port alternatif. |
| 8140 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8141 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8142 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8143 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8144 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8145 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8146 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8147 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8148 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8149 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8150 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8151 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8152 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8153 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8154 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8155 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8156 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8157 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8158 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8159 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8160 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8161 | TCP | ActiveMQ | Console web ActiveMQ. |
| 8162 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8163 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8164 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8165 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8166 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8167 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8168 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8169 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8170 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8171 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8172 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8173 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8174 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8175 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8176 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8177 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8178 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8179 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8180 | TCP | HTTP alternate | Web/app alternatif. |
|  8181 | TCP | HTTP alternate | Web/app fréquent. |
| 8182 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8183 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8184 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8185 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8186 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8187 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8188 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8189 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8190 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8191 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8192 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8193 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8194 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8195 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8196 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8197 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8198 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8199 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8200 | TCP | HashiCorp Vault | API Vault. |
| 8201 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8202 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8203 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8204 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8205 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8206 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8207 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8208 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8209 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8210 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8211 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8212 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8213 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8214 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8215 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8216 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8217 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8218 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8219 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8220 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8221 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8222 | TCP | NATS | Monitoring NATS ou port configuré. |
| 8223 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8224 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8225 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8226 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8227 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8228 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8229 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8230 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8231 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8232 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8233 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8234 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8235 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8236 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8237 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8238 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8239 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8240 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8241 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8242 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8243 | TCP | HTTPS alternate | HTTPS web alternatif. |
| 8244 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8245 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8246 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8247 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8248 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8249 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8250 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8251 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8252 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8253 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8254 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8255 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8256 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8257 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8258 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8259 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8260 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8261 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8262 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8263 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8264 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8265 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8266 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8267 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8268 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8269 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8270 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8271 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8272 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8273 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8274 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8275 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8276 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8277 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8278 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8279 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8280 | TCP | HTTP alternate | Port web alternatif. |
| 8281 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8282 | TCP | HTTP alternate | Port web/app alternatif. |
| 8283 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8284 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8285 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8286 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8287 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8288 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8289 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8290 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8291 | TCP | MikroTik Winbox | Administration MikroTik. |
| 8292 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8293 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8294 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8295 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8296 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8297 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8298 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8299 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8300 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8301 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8302 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8303 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8304 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8305 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8306 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8307 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8308 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8309 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8310 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8311 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8312 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8313 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8314 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8315 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8316 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8317 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8318 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8319 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8320 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8321 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8322 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8323 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8324 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8325 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8326 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8327 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8328 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8329 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8330 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8331 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8332 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8333 | TCP | Bitcoin | Peer-to-peer Bitcoin. |
|  8334 | TCP | Bitcoin | Port applicatif Bitcoin alternatif. |
| 8335 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8336 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8337 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8338 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8339 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8340 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8341 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8342 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8343 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8344 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8345 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8346 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8347 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8348 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8349 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8350 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8351 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8352 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8353 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8354 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8355 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8356 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8357 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8358 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8359 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8360 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8361 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8362 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8363 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8364 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8365 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8366 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8367 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8368 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8369 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8370 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8371 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8372 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8373 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8374 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8375 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8376 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8377 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8378 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8379 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8380 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8381 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8382 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8383 | TCP | HTTP alternate | Web/app alternatif. |
| 8384 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8385 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8386 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8387 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8388 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8389 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8390 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8391 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8392 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8393 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8394 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8395 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8396 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8397 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8398 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8399 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8400 | TCP | Port applicatif | Usage variable. |
| 8401 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8402 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8403 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8404 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8405 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8406 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8407 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8408 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8409 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8410 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8411 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8412 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8413 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8414 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8415 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8416 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8417 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8418 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8419 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8420 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8421 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8422 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8423 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8424 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8425 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8426 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8427 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8428 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8429 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8430 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8431 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8432 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8433 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8434 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8435 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8436 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8437 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8438 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8439 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8440 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8441 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8442 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8443 | TCP | HTTPS alternate | Web TLS alternatif, admin/API. |
|  8444 | TCP | HTTPS alternate | Port TLS alternatif. |
| 8445-8499 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8500 | TCP | Consul | API/UI Consul. |
| 8501 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8502 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8503 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8504 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8505 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8506 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8507 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8508 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8509 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8510 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8511 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8512 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8513 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8514 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8515 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8516 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8517 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8518 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8519 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8520 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8521 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8522 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8523 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8524 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8525 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8526 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8527 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8528 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8529 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8530 | TCP | WSUS HTTP | Windows Update Services HTTP. |
|  8531 | TCP | WSUS HTTPS | WSUS TLS. |
| 8532 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8533 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8534 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8535 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8536 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8537 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8538 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8539 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8540 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8541 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8542 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8543 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8544 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8545 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8546 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8547 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8548 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8549 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8550 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8551 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8552 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8553 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8554 | TCP | RTSP alternate | Streaming RTSP alternatif. |
| 8555 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8556 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8557 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8558 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8559 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8560 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8561 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8562 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8563 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8564 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8565 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8566 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8567 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8568 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8569 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8570 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8571 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8572 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8573 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8574 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8575 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8576 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8577 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8578 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8579 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8580 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8581 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8582 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8583 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8584 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8585 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8586 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8587 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8588 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8589 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8590 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8591 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8592 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8593 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8594 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8595 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8596 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8597 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8598 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8599 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8600 | TCP/UDP | Consul DNS | DNS Consul (config). |
| 8601 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8602 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8603 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8604 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8605 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8606 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8607 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8608 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8609 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8610 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8611 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8612 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8613 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8614 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8615 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8616 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8617 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8618 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8619 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8620 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8621 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8622 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8623 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8624 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8625 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8626 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8627 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8628 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8629 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8630 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8631 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8632 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8633 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8634 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8635 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8636 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8637 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8638 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8639 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8640 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8641 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8642 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8643 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8644 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8645 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8646 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8647 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8648 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8649 | TCP | Ganglia | Monitoring Ganglia. |
| 8650 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8651 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8652 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8653 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8654 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8655 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8656 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8657 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8658 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8659 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8660 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8661 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8662 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8663 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8664 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8665 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8666 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8667 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8668 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8669 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8670 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8671 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8672 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8673 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8674 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8675 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8676 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8677 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8678 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8679 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8680 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8681 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8682 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8683 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8684 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8685 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8686 | TCP | JMX | Gestion Java (config). |
| 8687-8760 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8761 | TCP | Eureka | Service registry Spring Eureka. |
| 8762-8879 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8880 | TCP | HTTP alternate | Port web alternatif. |
|  8881 | TCP | HTTP alternate | Port web alternatif. |
|  8882 | TCP | HTTP alternate | Port web alternatif. |
|  8883 | TCP | MQTT TLS | MQTT sécurisé. |
| 8884 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8885 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8886 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8887 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8888 | TCP | HTTP alternate | Web notebook, proxy, app/dev. |
|  8889 | TCP | HTTP alternate | Web/app alternatif. |
|  8890 | TCP | HTTP alternate | Web/app alternatif. |
| 8891 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8892 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8893 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8894 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8895 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8896 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8897 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8898 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 8899 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  8900 | TCP | Port applicatif | Usage variable. |
| 8901-8999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9000 | TCP | HTTP alternate | Web/app, dashboards, API. |
|  9001 | TCP | Tor OR alternate / app | Port variable; Tor relay souvent configuré. |
|  9002 | TCP | HTTP alternate | Web/app alternatif. |
|  9003 | TCP | Xdebug | Debug PHP (configuration). |
|  9004 | TCP | HTTP alternate | Port web/app alternatif. |
|  9005 | TCP | HTTP alternate | Port web/app alternatif. |
|  9006 | TCP | HTTP alternate | Port web/app alternatif. |
| 9007 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9008 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9009 | TCP | AJP alternate | Service AJP/application selon config. |
| 9010 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9015 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9017 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9018 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9019 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9020 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9021 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9022 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9023 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9024 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9025 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9026 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9027 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9028 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9029 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9030 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9031 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9032 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9033 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9034 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9035 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9036 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9037 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9038 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9039 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9040 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9041 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9042 | TCP | Cassandra CQL | Cassandra client. |
| 9043 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9044 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9045 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9046 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9047 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9048 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9049 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9050 | TCP | Tor SOCKS | Proxy SOCKS Tor (configuration courante). |
|  9051 | TCP | Tor control | Interface de contrôle Tor (à protéger). |
| 9052 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9053 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9054 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9055 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9056 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9057 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9058 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9059 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9060 | TCP | HTTP alternate | Web/app alternatif. |
| 9061 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9062 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9063 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9064 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9065 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9066 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9067 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9068 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9069 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9070 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9071 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9072 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9073 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9074 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9075 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9076 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9077 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9078 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9079 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9080 | TCP | HTTP alternate | Web/app alternatif. |
| 9081 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9082 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9083 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9084 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9085 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9086 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9087 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9088 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9089 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9090 | TCP | Prometheus | Monitoring Prometheus UI/API. |
|  9091 | TCP | Transmission | Interface Transmission; aussi Prometheus selon config. |
|  9092 | TCP | Kafka | Kafka broker. |
|  9093 | TCP | Kafka | Kafka/coordination selon configuration. |
|  9094 | TCP | Kafka | Kafka alternatif. |
| 9095 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9096 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9097 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9098 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9099 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9100 | TCP | JetDirect | Impression réseau. |
|  9101 | TCP | Bacula | Bacula director/worker selon rôle. |
|  9102 | TCP | Bacula | Bacula file daemon. |
|  9103 | TCP | Bacula | Bacula storage daemon. |
| 9104 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9105 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9106 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9107 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9108 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9109 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9110 | TCP | HTTP alternate | Web/app alternatif. |
|  9111 | TCP | HTTP alternate | Web/app alternatif. |
| 9112 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9113 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9114 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9115 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9116 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9117 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9118 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9119 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9120 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9121 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9122 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9123 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9124 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9125 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9126 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9127 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9128 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9129 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9130 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9131 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9132 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9133 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9134 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9135 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9136 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9137 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9138 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9139 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9140 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9141 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9142 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9143 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9144 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9145 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9146 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9147 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9148 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9149 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9150 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9151 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9152 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9153 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9154 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9155 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9156 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9157 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9158 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9159 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9160 | TCP | Cassandra | Service Cassandra alternatif. |
| 9161 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9162 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9163 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9164 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9165 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9166 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9167 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9168 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9169 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9170 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9171 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9172 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9173 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9174 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9175 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9176 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9177 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9178 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9179 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9180 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9181 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9182 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9183 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9184 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9185 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9186 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9187 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9188 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9189 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9190 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9191 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9192 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9193 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9194 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9195 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9196 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9197 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9198 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9199 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9200 | TCP | Elasticsearch | API HTTP Elasticsearch. |
|  9201 | TCP | Elasticsearch alternate | Port cluster/API alternatif. |
| 9202-9299 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9300 | TCP | Elasticsearch transport | Communication cluster Elasticsearch. |
| 9301-9417 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9418 | TCP | Git | Protocole Git natif. |
| 9419 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9420 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9421 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9422 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9423 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9424 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9425 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9426 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9427 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9428 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9429 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9430 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9431 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9432 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9433 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9434 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9435 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9436 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9437 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9438 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9439 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9440 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9441 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9442 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9443 | TCP | HTTPS alternate | Web TLS alternatif. |
|  9444 | TCP | HTTPS alternate | Web TLS alternatif. |
| 9445-9499 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9500 | TCP | Port applicatif | Usage variable. |
| 9501 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9502 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9503 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9504 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9505 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9506 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9507 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9508 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9509 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9510 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9511 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9512 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9513 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9514 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9515 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9516 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9517 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9518 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9519 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9520 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9521 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9522 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9523 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9524 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9525 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9526 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9527 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9528 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9529 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9530 | TCP | DNS management | Port applicatif DNS selon config. |
| 9531 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9532 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9533 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9534 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9535 | TCP | mDNS alternate | Service applicatif. |
| 9536-9599 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9600 | TCP | Logstash | API monitoring Logstash. |
| 9601-9665 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9666 | TCP | Port applicatif | Usage variable. |
| 9667-9875 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9876 | TCP | Port applicatif | Usage variable. |
| 9877 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9878 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9879 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9880 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9881 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9882 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9883 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9884 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9885 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9886 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9887 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9888 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9889 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9890 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9891 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9892 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9893 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9894 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9895 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9896 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9897 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9898 | TCP | HTTP alternate | Web/app alternatif. |
| 9899 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9900 | TCP | Port applicatif | Usage variable. |
| 9901-9989 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9990 | TCP | WildFly management | Interface gestion WildFly. |
| 9991 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9992 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9993 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9994 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9995 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9996 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9997 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 9998 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  9999 | TCP | HTTP alternate | Web/app/debug alternatif. |
|  10000 | TCP | Webmin | Administration Webmin (configuration). |
|  10001 | TCP | Webmin alternate | Port alternatif. |
| 10002 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10003 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10004 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10005 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10006 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10007 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10008 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10009 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10010 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10015 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10017 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10018 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10019 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10020 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10021 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10022 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10023 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10024 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10025 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10026 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10027 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10028 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10029 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10030 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10031 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10032 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10033 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10034 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10035 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10036 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10037 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10038 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10039 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10040 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10041 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10042 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10043 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10044 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10045 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10046 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10047 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10048 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10049 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  10050 | TCP | Zabbix agent | Agent Zabbix. |
|  10051 | TCP | Zabbix server | Réception Zabbix. |
| 10052 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10053 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10054 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10055 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10056 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10057 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10058 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10059 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10060 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10061 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10062 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10063 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10064 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10065 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10066 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10067 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10068 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10069 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10070 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10071 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10072 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10073 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10074 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10075 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10076 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10077 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10078 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10079 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  10080 | TCP | HTTP alternate | Port web alternatif. |
| 10081 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10082 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10083 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10084 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10085 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10086 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10087 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10088 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10089 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10090 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10091 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10092 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10093 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10094 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10095 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10096 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10097 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10098 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10099 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  10100 | TCP | Port applicatif | Usage variable. |
| 10101-10249 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  10250 | TCP | Kubernetes kubelet | API kubelet. |
| 10251 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10252 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10253 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 10254 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  10255 | TCP | Kubernetes kubelet read-only (legacy) | Endpoint historique, souvent désactivé. |
| 10256-10442 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  10443 | TCP | HTTPS alternate | TLS web alternatif. |
| 10444-10499 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  10500 | TCP | Port applicatif | Usage variable. |
| 10501-11210 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  11211 | TCP/UDP | Memcached | Cache mémoire Memcached. |
| 11212-11999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  12000 | TCP | Port applicatif | Usage variable. |
| 12001-12344 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  12345 | TCP | NetBus (historique) | Port associé à un ancien outil malveillant; usage actuel variable. |
| 12346-12999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  13000 | TCP | Port applicatif | Usage variable. |
| 13001-13305 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  13306 | TCP | MySQL alternate | MySQL port alternatif. |
| 13307-14329 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  14330 | TCP | MSSQL alternate | SQL Server alternatif. |
| 14331-14999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  15000 | TCP | Port applicatif | Usage variable. |
| 15001-15671 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  15672 | TCP | RabbitMQ management | Interface de gestion RabbitMQ. |
| 15673-15999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  16000 | TCP | Port applicatif | Usage variable. |
| 16001-16999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  17000 | TCP | Port applicatif | Usage variable. |
| 17001-18079 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  18080 | TCP | HTTP alternate | Web/app alternatif. |
| 18081-18180 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  18181 | TCP | HTTP alternate | Web/app alternatif. |
| 18182-18999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  19000 | TCP | Port applicatif | Usage variable. |
| 19001-19999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  20000 | TCP | DNP3 | Protocole industriel DNP3 (port fréquent). |
|  20001 | TCP | Port applicatif | Usage variable. |
| 20002-20442 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  20443 | TCP | HTTPS alternate | Port TLS alternatif. |
| 20444-20999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  21000 | TCP | Port applicatif | Usage variable. |
| 21001-21999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  22000 | TCP | Syncthing | Synchronisation Syncthing. |
| 22001-22099 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  22100 | TCP | Port applicatif | Usage variable. |
| 22101-22221 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  22222 | TCP | Port applicatif | Port custom courant. |
| 22223-22999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  23000 | TCP | Port applicatif | Usage variable. |
| 23001-23699 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  23700 | TCP | Port applicatif | Usage variable. |
| 23701-23999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  24000 | TCP | Port applicatif | Usage variable. |
| 24001-24999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  25000 | TCP | Port applicatif | Usage variable. |
| 25001-25564 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  25565 | TCP | Minecraft Java | Serveur Minecraft Java (port par défaut). |
| 25566-26999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  27000 | TCP | FlexLM | Gestion licences FlexNet (plage/config). |
| 27001 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27002 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27003 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27004 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27005 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27006 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27007 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27008 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27009 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27010 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 27014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  27015 | TCP/UDP | Steam / Source | Jeux, serveur et query selon configuration. |
| 27016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  27017 | TCP | MongoDB | Base MongoDB. |
|  27018 | TCP | MongoDB alternate | MongoDB shard/port alternatif. |
|  27019 | TCP | MongoDB config | MongoDB config server. |
| 27020-27999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  28000 | TCP | Port applicatif | Usage variable. |
| 28001 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28002 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28003 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28004 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28005 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28006 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28007 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28008 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28009 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28010 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28011 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28012 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28013 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28014 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28015 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
| 28016 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  28017 | TCP | MongoDB web legacy | Ancienne interface HTTP MongoDB, obsolète. |
| 28018-29999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  30000 | TCP | Port applicatif | Usage variable; aussi plage NodePort Kubernetes. |
|  30001 | TCP | Kubernetes NodePort | Port NodePort possible (plage par défaut 30000–32767). |
| 30002-30079 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  30080 | TCP | Kubernetes NodePort | NodePort fréquent pour HTTP. |
| 30081-30442 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  30443 | TCP | Kubernetes NodePort | NodePort fréquent pour HTTPS. |
| 30444-30999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  31000 | TCP | Kubernetes NodePort | NodePort possible. |
| 31001-31999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  32000 | TCP | Kubernetes NodePort | NodePort possible. |
| 32001-32763 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  32764 | TCP | Router backdoor (reports historiques) | Port signalé sur certains équipements anciens; ne pas présumer. |
| 32765-32999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  33000 | TCP | Port applicatif | Usage variable. |
| 33001-33889 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  33890 | TCP | RDP alternate | Port RDP personnalisé. |
| 33891-34999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  35000 | TCP | Port applicatif | Usage variable. |
| 35001-36999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  37000 | TCP | Port applicatif | Usage variable. |
| 37001-39999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  40000 | TCP | Port applicatif | Usage variable. |
| 40001-40999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  41000 | TCP | Port applicatif | Usage variable. |
| 41001-41999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  42000 | TCP | Port applicatif | Usage variable. |
| 42001-42999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  43000 | TCP | Port applicatif | Usage variable. |
| 43001-43999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  44000 | TCP | Port applicatif | Usage variable. |
| 44001-44999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  45000 | TCP | Port applicatif | Usage variable. |
| 45001-45999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  46000 | TCP | Port applicatif | Usage variable. |
| 46001-46999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  47000 | TCP | Port applicatif | Usage variable. |
| 47001-47999 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  48000 | TCP | Port applicatif | Usage variable. |
| 48001-49151 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
|  49152 | TCP/UDP | Début ports dynamiques | Début de la plage éphémère courante Windows/IANA. |
| 49153-65535 | TCP/UDP | Unassigned | Statut IANA à vérifier. |
### Ports système / Well-Known (0–1023)

Numéros signalés manquants :

`4, 6, 8, 10, 12, 14, 15, 16, 24, 26, 27, 28, 29, 30, 31, 32, 34, 35, 36, 40, 60, 81, 87, 428–442, 444, 446–463, 466–499, 501, 504–513, 516–519, 522–523, 525–529, 531–542, 545–547, 549–553, 555–559, 561–562, 564–586, 588–592, 594–599, 601–622, 624–630, 632–635, 637–638, 640–645, 649–650, 652, 655–656, 658–659, 661–665, 667–673, 675–690, 693–699, 703–705, 707–710, 712–719, 721–748, 752, 755–759, 761–764, 766, 768–771, 773, 775–776, 778–782, 784–799, 802–807, 809–842, 844–872, 874–879, 881–887, 889–901, 904–907, 909–910, 913–988, 991, 996–999, 1001–1022`

### Ports enregistrés (1024–49151)

#### 1024–4999

`1031–1032, 1034–1039, 1045–1049, 1051–1052, 1055–1057, 1059, 1061–1065, 1067–1079, 1081–1089, 1091–1097, 1101–1108, 1112–1119, 1121–1122, 1124–1157, 1159–1193, 1196–1213, 1215–1233, 1235–1240, 1242–1269, 1271–1310, 1312–1336, 1338–1351, 1353–1413, 1415–1432, 1435–1493, 1495–1499, 1501–1520, 1523, 1526–1532, 1534–1582, 1584–1603, 1605–1644, 1647–1700, 1702–1719, 1721–1722, 1724–1754, 1756–1760, 1762–1800, 1802–1811, 1814–1862, 1864–1882, 1884–1899, 1901–1934, 1936–1961, 1963–1971, 1973–1983, 1985–1997, 1999, 2006–2007, 2009, 2011–2019, 2023–2029, 2031–2048, 2051–2081, 2084–2085, 2088–2094, 2097–2099, 2105–2120, 2122–2143, 2145–2151, 2153–2180, 2182–2199, 2201–2221, 2224–2250, 2252–2300, 2302–2322, 2324–2374, 2378, 2381–2398, 2400, 2402–2403, 2405–2426, 2428–2442, 2444–2482, 2485–2499, 2501–2524, 2526–2545, 2547–2597, 2599–2600, 2602–2603, 2605–2637, 2639–2699, 2711–2716, 2718–2799, 2801–2808, 2810, 2812–2868, 2870–2874, 2876–2999, 3011–3029, 3031–3049, 3051–3073, 3075–3127, 3131–3259, 3261–3267, 3270–3299, 3301–3305, 3308–3309, 3311–3332, 3334–3388, 3391–3399, 3401–3477, 3480–3499, 3501–3543, 3545–3631, 3633–3689, 3691–3701, 3703–3723, 3725–3783, 3786–3799, 3801–3999, 4002–4039, 4041–4059, 4061–4079, 4081–4099, 4101–4110, 4112–4124, 4126–4199, 4201–4221, 4223–4241, 4243–4299, 4301–4320, 4322–4442, 4446–4499, 4501–4566, 4568–4661, 4663–4671, 4673–4710, 4712–4788, 4790–4847, 4849–4898, 4900–4999`

#### 5000–9999

`5008–5009, 5011–5059, 5062–5089, 5091–5099, 5101–5139, 5141–5149, 5151–5199, 5202–5221, 5224–5268, 5270–5279, 5281–5297, 5299–5352, 5354, 5356–5431, 5434–5499, 5501–5553, 5556–5600, 5602–5630, 5633–5665, 5667–5670, 5673–5682, 5685–5699, 5701–5799, 5801–5899, 5904–5983, 5987–5999, 6011–6059, 6062–6378, 6380–6442, 6444–6499, 6501–6513, 6515–6542, 6544–6659, 6670–6678, 6680–6696, 6698–6880, 6882–6968, 6970–6999, 7004–7069, 7071–7099, 7101–7198, 7201–7442, 7444–7473, 7475–7686, 7688–7776, 7778–7799, 7801–7999, 8011–8019, 8021–8029, 8031–8039, 8041, 8043–8079, 8101–8110, 8112–8122, 8124, 8126–8138, 8140–8160, 8162–8179, 8182–8199, 8201–8221, 8223–8242, 8244–8279, 8281, 8283–8290, 8292–8332, 8335–8382, 8384–8399, 8401–8442, 8445–8499, 8501–8529, 8532–8553, 8555–8599, 8601–8648, 8650–8685, 8687–8760, 8762–8879, 8884–8887, 8891–8899, 8901–8999, 9007–9008, 9010–9041, 9043–9049, 9052–9059, 9061–9079, 9081–9089, 9095–9099, 9104–9109, 9112–9159, 9161–9199, 9202–9299, 9301–9417, 9419–9442, 9445–9499, 9501–9529, 9531–9534, 9536–9599, 9601–9665, 9667–9875, 9877–9897, 9899, 9901–9989, 9991–9998`

#### 10000–49151

`10002–10049, 10052–10079, 10081–10099, 10101–10249, 10251–10254, 10256–10442, 10444–10499, 10501–11210, 11212–11370, 11372–11999, 12001–12344, 12346–12999, 13001–13305, 13307–14329, 14331–14999, 15001–15671, 15673–15999, 16001–16999, 17001–18079, 18081–18180, 18182–18999, 19001–19999, 20002–20442, 20444–20999, 21001–21999, 22001–22099, 22101–22221, 22223–22999, 23001–23699, 23701–23999, 24001–24999, 25001–25564, 25566–26999, 27001–27014, 27016, 27020–27999, 28001–28016, 28018–29999, 30002–30079, 30081–30442, 30444–30999, 31001–31999, 32001–32763, 32765–32999, 33001–33889, 33891–34999, 35001–36999, 37001–39999, 40001–40999, 41001–41999, 42001–42999, 43001–43999, 44001–44999, 45001–45999, 46001–46999, 47001–47999, 48001–49151`

### Ports dynamiques / privés (49152–65535)

Aucun numéro manquant signalé dans cette plage dans la liste fournie : la couverture précédente inclut `49152` et `49153–65535`.

