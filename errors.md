# Catalogue des codes d'erreur

> Codes classés par numéro croissant. Les significations peuvent varier selon le protocole, le système d'exploitation ou l'application. Ce catalogue rassemble les codes HTTP, DNS et erreurs réseau/système courantes, et n'est pas exhaustif de tous les logiciels.

## HTTP — codes de statut (100–599)

| Code | Nom | Signification / utilité |
|---:|---|---|
| 100 | Continue | Le client peut poursuivre l'envoi de la requête. |
| 101 | Switching Protocols | Le serveur accepte le changement de protocole demandé. |
| 102 | Processing | Requête en cours de traitement (WebDAV). |
| 103 | Early Hints | Informations préliminaires avant la réponse finale. |
| 200 | OK | Requête réussie. |
| 201 | Created | Ressource créée avec succès. |
| 202 | Accepted | Requête acceptée, traitement pas nécessairement terminé. |
| 203 | Non-Authoritative Information | Réponse modifiée par un intermédiaire. |
| 204 | No Content | Réussite sans contenu de réponse. |
| 205 | Reset Content | Le client doit réinitialiser la vue/formulaire. |
| 206 | Partial Content | Réponse partielle (requête Range). |
| 207 | Multi-Status | Résultats multiples (WebDAV). |
| 208 | Already Reported | Statut déjà rapporté (WebDAV). |
| 226 | IM Used | Réponse avec instance manipulation (HTTP Delta). |
| 300 | Multiple Choices | Plusieurs représentations possibles. |
| 301 | Moved Permanently | Ressource déplacée définitivement. |
| 302 | Found | Redirection temporaire (historiquement ambiguë). |
| 303 | See Other | Redirection vers une autre ressource, généralement en GET. |
| 304 | Not Modified | Ressource inchangée, cache réutilisable. |
| 305 | Use Proxy | Obsolète. |
| 306 | Unused | Code réservé/ancien, non utilisé. |
| 307 | Temporary Redirect | Redirection temporaire sans changer la méthode. |
| 308 | Permanent Redirect | Redirection permanente sans changer la méthode. |
| 400 | Bad Request | Requête invalide ou mal formée. |
| 401 | Unauthorized | Authentification requise ou invalide. |
| 402 | Payment Required | Réservé, parfois utilisé pour paiement. |
| 403 | Forbidden | Accès refusé. |
| 404 | Not Found | Ressource inexistante ou non trouvée. |
| 405 | Method Not Allowed | Méthode HTTP interdite pour cette ressource. |
| 406 | Not Acceptable | Format de réponse non acceptable selon les en-têtes. |
| 407 | Proxy Authentication Required | Authentification du proxy nécessaire. |
| 408 | Request Timeout | Le serveur a attendu trop longtemps la requête. |
| 409 | Conflict | Conflit avec l'état actuel de la ressource. |
| 410 | Gone | Ressource supprimée définitivement. |
| 411 | Length Required | Longueur de requête requise. |
| 412 | Precondition Failed | Condition préalable non satisfaite. |
| 413 | Content Too Large | Corps de requête trop volumineux. |
| 414 | URI Too Long | URI trop longue. |
| 415 | Unsupported Media Type | Type de média non pris en charge. |
| 416 | Range Not Satisfiable | Plage demandée non disponible. |
| 417 | Expectation Failed | Attente de requête non satisfaite. |
| 418 | I'm a teapot | Code humoristique défini dans RFC 2324, parfois réutilisé. |
| 421 | Misdirected Request | Requête dirigée vers un serveur incapable de la traiter. |
| 422 | Unprocessable Content | Contenu compris mais traitement impossible (validation). |
| 423 | Locked | Ressource verrouillée (WebDAV). |
| 424 | Failed Dependency | Dépendance échouée (WebDAV). |
| 425 | Too Early | Requête potentiellement rejouable refusée. |
| 426 | Upgrade Required | Changement de protocole requis. |
| 428 | Precondition Required | Condition préalable exigée. |
| 429 | Too Many Requests | Trop de requêtes; limitation de débit. |
| 431 | Request Header Fields Too Large | En-têtes trop volumineux. |
| 451 | Unavailable For Legal Reasons | Accès indisponible pour motif légal. |
| 500 | Internal Server Error | Erreur interne générique du serveur. |
| 501 | Not Implemented | Fonctionnalité/méthode non implémentée. |
| 502 | Bad Gateway | Réponse invalide reçue d'un serveur amont. |
| 503 | Service Unavailable | Service indisponible (maintenance/surcharge). |
| 504 | Gateway Timeout | Délai dépassé auprès du serveur amont. |
| 505 | HTTP Version Not Supported | Version HTTP non prise en charge. |
| 506 | Variant Also Negotiates | Erreur de négociation de contenu. |
| 507 | Insufficient Storage | Stockage insuffisant (WebDAV). |
| 508 | Loop Detected | Boucle détectée (WebDAV). |
| 510 | Not Extended | Extensions supplémentaires requises. |
| 511 | Network Authentication Required | Authentification du réseau requise. |

## DNS — codes RCODE

| Code | Nom | Signification |
|---:|---|---|
| 0 | NOERROR | Réponse DNS sans erreur; le résultat peut être vide selon le type de requête. |
| 1 | FORMERR | Requête DNS mal formée. |
| 2 | SERVFAIL | Le serveur DNS n'a pas pu traiter la requête. |
| 3 | NXDOMAIN | Nom de domaine inexistant. |
| 4 | NOTIMP | Opération non prise en charge. |
| 5 | REFUSED | Requête refusée par le serveur DNS. |
| 6 | YXDOMAIN | Nom existe alors qu'il ne devrait pas (rare/legacy). |
| 7 | YXRRSET | RRset existe alors qu'il ne devrait pas (rare/legacy). |
| 8 | NXRRSET | RRset demandé absent (rare/legacy). |
| 9 | NOTAUTH | Serveur non autoritaire ou autorisation insuffisante. |
| 10 | NOTZONE | Données hors zone attendue (rare/legacy). |
| 16 | BADVERS / BADSIG | Version EDNS incorrecte ou ancien code de signature selon contexte. |
| 17 | BADKEY | Clé TSIG invalide. |
| 18 | BADTIME | Écart de temps TSIG invalide. |
| 19 | BADMODE | Mode TKEY invalide. |
| 20 | BADNAME | Nom TKEY invalide. |
| 21 | BADALG | Algorithme TKEY invalide. |
| 22 | BADTRUNC | Troncature TSIG invalide. |
| 23 | BADCOOKIE | Cookie DNS invalide. |

## Erreurs réseau et socket (codes POSIX courants)

> Les numéros ci-dessous sont typiques des systèmes Linux; d'autres systèmes peuvent utiliser une numérotation différente. La signification est donnée par le nom symbolique.

| Numéro (Linux courant) | Nom | Description |
|---:|---|---|
| 1 | EPERM | Opération non autorisée. |
| 2 | ENOENT | Fichier ou répertoire inexistant. |
| 3 | ESRCH | Processus inexistant. |
| 4 | EINTR | Appel interrompu par un signal. |
| 5 | EIO | Erreur d'entrée/sortie. |
| 6 | ENXIO | Périphérique ou adresse inexistante. |
| 7 | E2BIG | Liste d'arguments trop longue. |
| 8 | ENOEXEC | Format exécutable invalide. |
| 9 | EBADF | Descripteur de fichier invalide. |
| 10 | ECHILD | Aucun processus enfant disponible. |
| 11 | EAGAIN / EWOULDBLOCK | Ressource temporairement indisponible; réessayer. |
| 12 | ENOMEM | Mémoire insuffisante. |
| 13 | EACCES | Permission refusée. |
| 14 | EFAULT | Adresse mémoire invalide. |
| 15 | ENOTBLK | Périphérique bloc requis. |
| 16 | EBUSY | Ressource occupée. |
| 17 | EEXIST | Fichier déjà existant. |
| 18 | EXDEV | Opération inter-systèmes de fichiers non permise. |
| 19 | ENODEV | Périphérique inexistant. |
| 20 | ENOTDIR | Élément n'est pas un répertoire. |
| 21 | EISDIR | Élément est un répertoire. |
| 22 | EINVAL | Argument invalide. |
| 23 | ENFILE | Limite globale de fichiers ouverts atteinte. |
| 24 | EMFILE | Limite de fichiers ouverts du processus atteinte. |
| 25 | ENOTTY | Opération ioctl non applicable. |
| 26 | ETXTBSY | Fichier exécutable occupé. |
| 27 | EFBIG | Fichier trop volumineux. |
| 28 | ENOSPC | Espace disque insuffisant. |
| 29 | ESPIPE | Opération seek impossible sur ce flux. |
| 30 | EROFS | Système de fichiers en lecture seule. |
| 31 | EMLINK | Trop de liens. |
| 32 | EPIPE | Pipe/socket fermé côté distant; broken pipe. |
| 33 | EDOM | Erreur de domaine mathématique. |
| 34 | ERANGE | Résultat hors plage. |
| 35 | EDEADLK | Interblocage détecté/risque. |
| 36 | ENAMETOOLONG | Nom ou chemin trop long. |
| 37 | ENOLCK | Verrou indisponible. |
| 38 | ENOSYS | Fonction système non implémentée. |
| 39 | ENOTEMPTY | Répertoire non vide. |
| 40 | ELOOP | Trop de liens symboliques. |
| 42 | ENOMSG | Message absent. |
| 43 | EIDRM | Identifiant supprimé. |
| 48 | ENOTSOCK | Descripteur n'est pas un socket. |
| 49 | EDESTADDRREQ | Adresse destination requise. |
| 50 | EMSGSIZE | Message trop grand. |
| 51 | EPROTOTYPE | Type de protocole incorrect. |
| 52 | ENOPROTOOPT | Option de protocole inconnue. |
| 53 | EPROTONOSUPPORT | Protocole non pris en charge. |
| 54 | ESOCKTNOSUPPORT | Type de socket non pris en charge. |
| 55 | EOPNOTSUPP | Opération non prise en charge par socket. |
| 56 | EPFNOSUPPORT | Famille de protocoles non prise en charge. |
| 57 | EAFNOSUPPORT | Famille d'adresses non prise en charge. |
| 58 | EADDRINUSE | Adresse/port déjà utilisé. |
| 59 | EADDRNOTAVAIL | Adresse non disponible. |
| 60 | ENETDOWN | Réseau désactivé. |
| 61 | ENETUNREACH | Réseau inaccessible. |
| 62 | ENETRESET | Connexion réinitialisée par le réseau. |
| 63 | ECONNABORTED | Connexion avortée. |
| 64 | ECONNRESET | Connexion réinitialisée par le pair. |
| 65 | ENOBUFS | Tampons réseau insuffisants. |
| 66 | EISCONN | Socket déjà connecté. |
| 67 | ENOTCONN | Socket non connecté. |
| 68 | ESHUTDOWN | Socket arrêtée. |
| 69 | ETOOMANYREFS | Trop de références. |
| 70 | ETIMEDOUT | Délai de connexion/opération dépassé. |
| 71 | ECONNREFUSED | Connexion refusée. |
| 72 | EHOSTDOWN | Hôte arrêté. |
| 73 | EHOSTUNREACH | Hôte inaccessible. |
| 74 | EALREADY | Opération déjà en cours. |
| 75 | EINPROGRESS | Opération en cours. |
| 76 | ESTALE | Référence de fichier périmée. |
| 77 | EDQUOT | Quota dépassé. |
| 78 | ENOMEDIUM | Aucun média présent. |
| 79 | EMEDIUMTYPE | Type de média incorrect. |
| 80 | ECANCELED | Opération annulée. |
| 81 | ENOKEY | Clé requise absente. |
| 82 | EKEYEXPIRED | Clé expirée. |
| 83 | EKEYREVOKED | Clé révoquée. |
| 84 | EKEYREJECTED | Clé rejetée. |

## TLS / certificats — messages et erreurs fréquentes

| Code / message | Nom | Description |
|---|---|---|
|  | CERTIFICATE_VERIFY_FAILED | Vérification du certificat échouée (CA, chaîne, nom, validité). |
|  | SSL_ERROR_HANDSHAKE_FAILURE | Échec de négociation TLS. |
|  | SSL_ERROR_WANT_READ | La bibliothèque TLS attend des données. |
|  | SSL_ERROR_WANT_WRITE | La bibliothèque TLS attend l'écriture. |
|  | TLSV1_ALERT_PROTOCOL_VERSION | Version TLS incompatible. |
|  | TLSV1_ALERT_UNKNOWN_CA | Autorité de certification non reconnue. |
|  | TLSV1_ALERT_CERTIFICATE_EXPIRED | Certificat expiré. |
|  | TLSV1_ALERT_BAD_CERTIFICATE | Certificat rejeté ou invalide. |
|  | ERR_CERT_COMMON_NAME_INVALID | Nom du certificat ne correspond pas au site. |
|  | ERR_CERT_DATE_INVALID | Certificat hors période de validité. |
|  | ERR_CERT_AUTHORITY_INVALID | Autorité de certification non approuvée. |
|  | ERR_SSL_PROTOCOL_ERROR | Erreur de protocole TLS/SSL générique. |
|  | ERR_SSL_VERSION_OR_CIPHER_MISMATCH | Version ou suite cryptographique incompatible. |

## Erreurs courantes côté navigateur / client

| Code / message | Nom | Description |
|---|---|---|
|  | ERR_CONNECTION_REFUSED | Connexion TCP refusée. |
|  | ERR_CONNECTION_RESET | Connexion interrompue/réinitialisée. |
|  | ERR_CONNECTION_TIMED_OUT | Délai de connexion dépassé. |
|  | ERR_NAME_NOT_RESOLVED | Résolution DNS du nom impossible. |
|  | ERR_NETWORK_CHANGED | Configuration réseau modifiée pendant la requête. |
|  | ERR_INTERNET_DISCONNECTED | Aucune connexion Internet détectée. |
|  | ERR_ADDRESS_UNREACHABLE | Adresse réseau inaccessible. |
|  | ERR_BLOCKED_BY_CLIENT | Requête bloquée par le client (extension/règle). |
|  | ERR_TOO_MANY_REDIRECTS | Boucle ou trop de redirections. |
|  | ERR_CACHE_MISS | Données cache requises absentes. |
|  | ERR_INVALID_URL | URL invalide. |
|  | ERR_ABORTED | Opération annulée. |

## Rappels

- **4xx HTTP** : erreur côté requête/client, accès, ressource, validation ou limitation.
- **5xx HTTP** : erreur côté serveur, passerelle ou service amont.
- **DNS NXDOMAIN** : le nom demandé n'existe pas; **SERVFAIL** : le serveur DNS n'a pas pu répondre correctement.
- **ECONNREFUSED** : le serveur/port refuse; **ETIMEDOUT** : aucune réponse avant délai; **ENETUNREACH/EHOSTUNREACH** : route ou destination inaccessible.
- Les messages exacts peuvent varier selon navigateur, OS, bibliothèque, serveur et version.
