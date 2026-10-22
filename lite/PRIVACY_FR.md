---
layout: lite
---

# Politique de confidentialité de sCollectPlay et sCollectPlay Lite

Mise à jour : 2026-10-22

## En bref

sCollectPlay et sCollectPlay Lite ne collectent, n’enregistrent et ne transmettent
**aucune** donnée personnelle. Les apps travaillent exclusivement sur votre Mac ou votre PC Windows. Il n’y a
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

## Sous Windows

Les sections ci-dessus décrivent le Mac. Sous Windows, sCollectPlay et sCollectPlay Lite enregistrent les éléments
suivants exclusivement en local, dans le dossier de données de l’app (`%LOCALAPPDATA%\Packages\<paquet>\LocalState` et `Settings`) :

- **Les réglages et la position de la fenêtre.**
- **La dernière source choisie** — dossiers scannés, un fichier XML iTunes ou une bibliothèque sCollect — et le
  résultat du dernier scan.
- **La correspondance entre les dossiers Mac d’une bibliothèque et des dossiers de votre PC** (chemins de
  dossiers uniquement).
- **Dans sCollectPlay, en plus :** vos propres playlists, la liste des derniers dossiers, fichiers XML et
  bibliothèques utilisés, le tri et l’état du navigateur de colonnes.
- **Un journal des erreurs** (`fehler.log`), qui reste sur votre PC.

Tout cela est supprimé lorsque vous désinstallez l’app.

L’app ne lit les fichiers médias et les fichiers XML qu’aux emplacements que vous sélectionnez ; une bibliothèque
sCollect est uniquement lue. Elle n’établit aucune connexion réseau propre, n’utilise aucun service d’analyse et
n’affiche aucune publicité. Les fichiers que Windows ne lit pas lui-même sont transmis au programme par défaut pour ce
type de fichier, que vous choisissez dans Windows.

Si vous exportez dans sCollectPlay une playlist pour VLC ou un appareil, l’app copie ses fichiers dans le dossier
que vous choisissez. Sous Windows, elle ne supprime aucun fichier média.

## Microsoft Store

Sous Windows, l’achat (sCollectPlay), le téléchargement et les mises à jour passent par le Microsoft Store ; la
déclaration de confidentialité de Microsoft s’y applique. sCollectPlay Lite est gratuite et mentionne la version complète.

## Aucune transmission, aucune analyse

Il n’y a pas de publicité, pas de services d’analyse, pas de rapports de plantage à des
tiers et pas de comptes.

## Contact

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
