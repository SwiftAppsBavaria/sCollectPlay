---
layout: lite
---

# Aide de sCollectPlay et sCollectPlay Lite

## Ce que fait l’app

sCollectPlay lit la musique, les livres audio, les podcasts, les films et les e-books
directement depuis vos dossiers, depuis un XML iTunes ou Apple Music, ou depuis une
bibliothèque sCollect. Elle ne copie rien, n’importe rien et n’écrit rien dans vos
fichiers.

## Premiers pas

Au démarrage, choisissez l’une des trois sources — ou plus tard par le menu **Fichier** :

1. **Scanner le dossier…** — n’importe quel dossier avec ses sous-dossiers.
2. **Ouvrir la bibliothèque XML…** — un fichier XML exporté depuis Apple Music. Vous le
   créez dans Apple Music via **Fichier → Bibliothèque → Exporter la bibliothèque**.
3. **Choisir la bibliothèque sCollect…** (⇧⌘O) — le dossier principal d’une bibliothèque
   créée avec sCollect.

La barre de titre de la fenêtre indique ensuite ce qui est chargé, par exemple
Dossier « Musique » ; si vous pointez sur le titre, le chemin complet apparaît.

## Questions fréquentes

**Pourquoi les types de médias s’appellent-ils « jusqu’à 10 min » ou « 30–60 min » ?**
Lors du scan d’un dossier, l’app ne sait pas si un fichier est une chanson, un livre audio
ou un podcast — aucun dossier ne le dit. C’est pourquoi elle classe l’audio et la vidéo
par durée. Avec un XML ou une bibliothèque sCollect, les vrais types sont là : Musique,
Livre audio, Long métrage, etc.

**L’app demande un dossier que j’ai déjà choisi.**
macOS n’autorise une app à accéder qu’aux dossiers que vous lui donnez expressément. Si
les fichiers d’un XML ou les dossiers médias d’une bibliothèque se trouvent en dehors du
dossier choisi, l’app demande une fois chacun de ces dossiers et mémorise l’autorisation.

**Un titre affiche « Fichier illisible ».**
Il manque à l’app l’autorisation pour le dossier où se trouve le fichier — ou le disque
n’est pas connecté. Sous **Réglages → Général → Dossier média**, vous voyez quels dossiers
sont autorisés et pouvez, avec **Choisir**, accorder une autorisation manquante.

**Un film s’ouvre dans un autre programme.**
Les formats que macOS ne lit pas lui-même — comme MKV, AVI ou DivX —, l’app les transmet
à un autre lecteur. Lequel, vous le réglez sous **Réglages → Lecture/Playlist → Lecteur
externe pour les codecs non pris en charge** ; VLC et IINA sont reconnus s’ils sont
installés.

**Au démarrage, l’app demande si elle doit charger une source sur un volume réseau.**
Un volume réseau inaccessible pourrait retarder longuement le démarrage. La question se
désactive avec **Ne plus demander** et se réactive sous **Réglages → Général**.

**Puis-je modifier les tags ou les informations des titres ?**
Non. sCollectPlay est un lecteur et ne modifie aucune métadonnée.

**Comment envoyer une sélection dans Apple Music ?**
Par le menu contextuel **Envoyer comme playlist à Apple Music** ou par **Fichier →
Envoyer la playlist à Apple Music…**. La première fois, macOS demande si l’app peut
piloter Apple Music.

**Que fait sCollectPlay que l’édition Lite ne fait pas ?**
sCollectPlay offre en plus le navigateur de colonnes, les playlists personnelles et
intelligentes, la réunion de plusieurs dossiers, les listes des sources récemment
utilisées et la restauration de la dernière source au démarrage. sCollectPlay Lite lit
une source par session.

**Puis-je annuler une suppression ?**
Oui, avec ⌘Z, tant que le fichier se trouve encore dans la corbeille. Sur les disques sans
corbeille, l’app demande d’abord s’il faut supprimer définitivement — cela ne peut pas
être annulé.

## Contact

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net
