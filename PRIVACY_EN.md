# Privacy Policy for sCollectPlay and sCollectPlay Lite

Last updated: 2026-10-01

## In brief

sCollectPlay and sCollectPlay Lite collect, store and transmit **no** personal data. The
apps work exclusively on your Mac. There are no accounts, no cloud connection, no analytics
services and no advertising.

## What data the app processes

The app reads the media files in the folders you have explicitly handed to it — by
choosing them in the open dialog: a folder to scan, an iTunes or Apple Music XML, or an
sCollect library. What is read is the file name, file size, date and the file’s metadata,
and for an XML or a library also its catalog information.

Without your selection the app accesses no file at all. macOS enforces this through the
App Sandbox.

## What the app stores on your Mac

- **Settings and window positions** in the app’s protected container folder.
- **The permission from macOS to reopen your folders at the next launch.** What is stored
  are folder paths, not file contents. It is the only way for the app not to have to ask
  again at every launch.
- **In sCollectPlay additionally:** the list of recently used folders, XML files and
  libraries, your own playlists, the sort order and the state of the column browser —
  likewise in the app’s protected container folder.

All of this is gone once you delete the app.

## Two permissions that may raise questions

**Network access.** The app asks for it because macOS shows the built-in help window
empty without this permission — the help is rendered by a system component that needs
it, even though it only loads files from the program itself. The app calls up **no
address on the internet** of its own accord, downloads nothing and reports nothing.

Folders on network volumes (SMB, NFS) are reached by the app through your Mac’s file
system, not through a connection of its own.

**Controlling Apple Music.** When you send a selection to Apple Music as a playlist, the
app opens Apple Music with a playlist it has created and, if you wish, replaces one of the
same name that is already there. macOS asks for your consent for that, and it is asked
the first time. The app controls no other programs.

## Your files

The app writes no tags and changes no metadata in your files.

Only when you expressly delete a file does the app put it in the macOS Trash and remove it
from the list; if it comes from an sCollect library, that library’s catalog is adjusted
accordingly. On drives without a Trash the app asks beforehand whether the file should be
deleted for good.

## No sharing, no analytics

There is no advertising, there are no analytics services, no crash reports to third
parties and no accounts.

## Contact

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
