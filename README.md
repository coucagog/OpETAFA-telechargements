# OpETAFA — téléchargements

OpETAFA affiche les tests d'acuité visuelle de loin sur un écran de la salle, piloté par un téléphone,
un clavier ou une télécommande. Ce dépôt ne contient que les **fichiers à installer** ; le code est
ailleurs.

**Dernière version : [page des téléchargements](../../releases/latest)**

## Application TV Android — `OpETAFA-<version>-tv.apk`

L'écran et le relais tournent sur la TV, sans PC ; le téléphone s'y relie par le QR affiché.

1. Sur la TV, autoriser l'installation d'applications inconnues pour l'application qui servira à
   télécharger (navigateur, gestionnaire de fichiers, ou une application de téléchargement comme
   *Downloader*).
2. Télécharger le fichier `.apk` depuis la page ci-dessus, l'ouvrir, installer.
   Avec *Downloader*, il suffit de taper le lien court **`da.gd/opetafa`** (version 0.1.0).
3. Lancer OpETAFA, relier un téléphone par le QR, puis calibrer l'écran.

Les mises à jour s'installent par-dessus, le profil de la salle (code, calibration) est gardé.
L'application est signée par la clé d'OpETAFA ; empreinte SHA-256 du certificat :
`45:50:6C:16:84:B6:AB:CC:05:FE:F8:9F:02:82:3E:37:FD:6F:61:87:88:E9:24:43:EA:07:EE:F0:93:1C:4E:60`.

## PC Windows — `OpETAFA-<version>-windows.zip`

Décompresser l'archive et suivre le guide d'installation qu'elle contient.

## Licence

MIT. Signature : ETAFA by MLS.
