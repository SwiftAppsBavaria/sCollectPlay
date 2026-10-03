# sCollectPlay and sCollectPlay Lite Help

## What the app does

sCollectPlay plays music, audiobooks, podcasts, films and e-books straight from your
folders, from an iTunes or Apple Music XML, or from an sCollect library. It copies
nothing, imports nothing and writes nothing into your files.

## First steps

Choose one of the three sources at launch — or later through the **File** menu:

1. **Scan Folder…** — any folder including its subfolders.
2. **Open XML Library…** — an XML file exported from Apple Music. You create it in Apple
   Music under **File → Library → Export Library**.
3. **Choose sCollect Library…** (⇧⌘O) — the main folder of a library created with
   sCollect.

The window’s title bar then names what is loaded, for example Folder “Music”; point at
the title and the full path appears.

## Frequently asked questions

**Why are the media types called “up to 10 min” or “30–60 min”?**
When scanning a folder, the app doesn’t know whether a file is a song, an audiobook or a
podcast — no folder says so. That is why it sorts audio and video by duration. With an
XML or an sCollect library the real types are there: Music, Audiobook, Feature Film and
so on.

**The app asks for a folder I have already chosen.**
macOS only allows an app to access folders you expressly give it. If the files of an XML
or the media folders of a library lie outside the chosen folder, the app asks once for
each of these folders and remembers the permission.

**A track reports “File not readable”.**
The app lacks permission for the folder the file is in — or the drive isn’t connected.
Under **Settings → General → Media Folder** you can see which folders are permitted, and
with **Choose** you can grant a missing permission.

**A film opens in another program.**
Formats that macOS doesn’t play itself — such as MKV, AVI or DivX — the app hands to
another player. Which one, you set under **Settings → Playback/Playlist → External player
for unsupported codecs**; VLC and IINA are detected if they are installed.

**At launch the app asks whether to load a source on a network volume.**
A network volume that can’t be reached could hold up the launch for a long time. The
question can be turned off with **Don't ask again** and turned back on under
**Settings → General**.

**Can I edit tags or track information?**
No. sCollectPlay is a player and changes no metadata.

**How do I get a selection into Apple Music?**
Through the context menu **Send as Playlist to Apple Music** or through **File → Send
Playlist to Apple Music…**. The first time, macOS asks whether the app may control Apple
Music.

**What can sCollectPlay do that the Lite edition can’t?**
sCollectPlay additionally offers the column browser, choosing which columns to show, your own and smart playlists,
combining several folders, the lists of recently used sources and restoring the last
source at launch. sCollectPlay Lite plays one source per session.

**Can I undo a deletion?**
Yes, with ⌘Z, as long as the file is still in the Trash. On drives without a Trash the
app asks beforehand whether to delete for good — that cannot be undone.

## Contact

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net
