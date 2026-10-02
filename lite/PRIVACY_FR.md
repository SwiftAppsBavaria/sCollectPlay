---
layout: lite
---

# Politique de confidentialité de sCollectPlay et sCollectPlay Lite

Mise à jour : 2026-10-01

## En bref

sCollectPlay et sCollectPlay Lite ne collectent, n’enregistrent et ne transmettent
**aucune** donnée personnelle. Les apps travaillent exclusivement sur votre Mac. Il n’y a
ni comptes, ni connexion au cloud, ni services d’analyse, ni publicité.

## Quelles données l’app traite

L’app lit les fichiers médias dans les dossiers que vous lui avez expressément confiés —
par une sélection dans la fenêtre d’ouverture : un dossier à scanner, un XML iTunes ou
Apple Music, ou une bibliothèque sCollect. Sont lus le nom du fichier, sa taille, sa date
et ses métadonnées, et pour un XML ou une bibliothèque, en plus, les données de son
catalogue.

Sans votre sélection, l’app n’accède à aucun fichier. macOS l’impose par la sandbox de
l’app.

## Ce que l’app dépose sur votre Mac

- **Les réglages et les positions des fenêtres** dans le dossier protégé de l’app.
- **L’autorisation de macOS de rouvrir vos dossiers au prochain démarrage.** Ce sont des
  chemins de dossiers qui sont enregistrés, pas des contenus de fichiers. C’est le seul
  moyen pour que l’app n’ait pas à redemander à chaque démarrage.
- **Dans sCollectPlay, en plus :** la liste des derniers dossiers, fichiers XML et
  bibliothèques utilisés, vos propres playlists, le tri et l’état du navigateur de
  colonnes — également dans le dossier protégé de l’app.

Tout cela disparaît lorsque vous supprimez l’app.

## Deux autorisations qui peuvent soulever des questions

**L’accès au réseau.** L’app le demande parce que macOS affiche vide la fenêtre d’aide
intégrée sans cette autorisation — l’aide est présentée par un composant du système qui
en a besoin, même s’il ne charge que des fichiers du programme lui-même. L’app
n’appelle d’elle-même **aucune adresse sur Internet**, ne télécharge rien et ne signale
rien.

Les dossiers sur des volumes réseau (SMB, NFS) sont atteints par l’app via le système de
fichiers de votre Mac, et non par une connexion propre.

**Le pilotage d’Apple Music.** Lorsque vous envoyez une sélection à Apple Music comme
playlist, l’app ouvre Apple Music avec une playlist qu’elle a créée et, si vous le
souhaitez, remplace une playlist du même nom qui s’y trouve déjà. macOS demande votre
accord pour cela, et il est demandé la première fois. L’app ne pilote aucun autre
programme.

## Vos fichiers

L’app n’écrit aucun tag et ne modifie aucune métadonnée de vos fichiers.

Seulement lorsque vous supprimez expressément un fichier, l’app le place dans la corbeille
de macOS et le retire de la liste ; s’il provient d’une bibliothèque sCollect, le
catalogue de celle-ci est adapté en conséquence. Sur les disques sans corbeille, l’app
demande d’abord si le fichier doit être supprimé définitivement.

## Aucune transmission, aucune analyse

Il n’y a pas de publicité, pas de services d’analyse, pas de rapports de plantage à des
tiers et pas de comptes.

## Contact

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
