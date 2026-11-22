# Politique de confidentialité de MyIslandX

*Dernière mise à jour : 22 novembre 2026*

MyIslandX est une application Windows qui affiche des informations en haut de l'écran (musique, notifications, prières, météo, agenda…).
**Elle n'a pas de compte utilisateur, n'utilise aucun outil de publicité ni de statistiques, et ne vend aucune donnée.**

## Ce qui reste sur ton PC

Tout ce que l'application lit ou enregistre reste sur ton ordinateur, dans `%AppData%\MyIslandX` :

- tes réglages, tâches, comptes à rebours, raccourcis et fichiers de l'étagère (seulement leur emplacement) ;
- un journal technique (`log.txt`) pour diagnostiquer les erreurs, que tu peux supprimer à tout moment.

L'application lit, **sans jamais les envoyer** :

- les notifications de tes applications (pour les afficher dans l'île), avec ton accord donné à Windows ;
- la musique en cours, le volume, la luminosité, la batterie, l'état du réseau ;
- les applications qui utilisent le micro, la caméra ou le partage d'écran (pour les voyants) ;
- le presse-papiers (historique gardé **en mémoire seulement**, jamais enregistré) ;
- les captures d'écran du dossier Images › Captures d'écran.

## Ce qui sort de ton PC

| Service | Données envoyées | Pourquoi |
| --- | --- | --- |
| MET Norway (api.met.no) | Position arrondie à environ 1 km | Météo |
| Tes agendas (Google, Outlook, iCloud…) | Rien, l'application télécharge seulement le lien iCal que tu as fourni | Afficher tes événements |
| Google Agenda (connexion Google, si tu l'actives) | Ton jeton de connexion ; l'application lit tes événements et ajoute ceux que tu crées depuis l'île | Afficher et ajouter des événements. Le jeton est chiffré par Windows sur ton PC, jamais envoyé ailleurs. Tu peux te déconnecter à tout moment dans les réglages ou sur myaccount.google.com/permissions |
| Microsoft Store | Géré par Microsoft | Achat de la version Pro, mises à jour |

Les horaires de prière sont calculés sur ton PC, sans connexion.
La position vient de Windows (si tu l'autorises) ou de la ville que tu choisis.

## Tes droits

Tu peux supprimer toutes les données en désinstallant l'application et en supprimant le dossier `%AppData%\MyIslandX`.
Pour toute question : [ton adresse e-mail de contact].

---

# MyIslandX privacy policy (English)

MyIslandX has no user account, no ads, no analytics and sells no data.
Settings, tasks and logs stay on your PC in `%AppData%\MyIslandX`. Notifications, media, clipboard (memory only) and
microphone/camera usage are read locally and never sent. Weather requests send an approximate location (~1 km) to MET Norway.
Calendars are downloaded from the iCal links you provide. The Android companion app communicates only on your local network.
Contact: [your contact email].
