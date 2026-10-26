# SatSSTV

Station satellite et SSTV pour Windows et Linux, par **F4LPS** — réception et émission SSTV, suivi des satellites
(globe 3D, passages, correction Doppler), pilotage CAT du poste, images Meteor-M, logs et Tracker F4LPS.

## Télécharger

➡️ **[Dernière version](https://github.com/F4LPS/SatSSTV/releases/latest)** : `SatSSTV-Setup-x.y.z.exe`

L’installateur ne demande pas de droits administrateur (installation dans `%LOCALAPPDATA%\Programs\SatSSTV`).
Il installe SatSSTV et le **Tracker F4LPS** (carte commune avec MultiDigi et CW Terminal).
Vos profils, images et enregistrements (`%LOCALAPPDATA%\SatSSTV`) sont conservés lors d’une mise à jour ou d’une désinstallation.
SatSSTV signale lui-même les nouvelles versions par une bulle au démarrage.

### Linux (PC 64 bits : Ubuntu 20.04, Debian 11, Mint 20 ou plus récents)

- `SatSSTV-x.y.z-x86_64.AppImage` : sans installation, `chmod +x SatSSTV-*.AppImage` puis l’ouvrir.
- `satsstv_x.y.z_amd64.deb` : `sudo apt install ./satsstv_x.y.z_amd64.deb`, SatSSTV apparaît dans le menu.

Sous Linux : ports série `/dev/ttyUSB0` (ajouter l’utilisateur au groupe `dialout`), CAT direct, Hamlib ou FLRig
(OmniRig est réservé à Windows), notifications par `notify-send`.

## Principales fonctions

- Décodage et émission SSTV (Robot, Martin, Scottie, PD…), FSK-ID, galeries, templates et écriture « affiche »
- **SSTV numérique DRM** compatible EasyPal / QSSTV (Atelier DRM) : réception et émission, modes A / B / E,
  QAM 4 / 16 / 64, Reed-Solomon RS1 à RS4, waterfall DRM et constellation
- Fréquences SSTV de chaque bande en un clic (fréquence et mode du poste), ISS SSTV sur 437,550 MHz
- Suivi des satellites : globe 3D (image NASA Blue Marble), passages, Doppler automatique, passages armés,
  enregistrement audio des passages, notifications bureau / Discord / Telegram
- CAT : Icom CI-V, Yaesu, Kenwood / Elecraft, OmniRig, Ham Radio Deluxe, Hamlib, FLRig
- Recherche des correspondants (QRZ.com, HamQTH…), log vers fichier ADIF, HRD, N1MM+, Log4OM, eQSL, ClubLog,
  WaveLog, QRZ.com, LoTW…
- Atelier météo : décodage des images Meteor-M LRPT
- Fusion des images ARISS reçues sur plusieurs passages

Les crédits et licences des éléments tiers (Natural Earth, NASA Blue Marble, décodeurs Meteor sous licence MIT)
sont installés avec le programme (`THIRD_PARTY_NOTICES.txt`, `CREDITS-CARTES.md`).

73 de F4LPS
