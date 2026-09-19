OUR STORY — a personal anniversary website
===========================================

WHAT THIS IS
------------
A single self-contained webpage (index.html) — no server, no install,
no dependencies. Open it in any modern browser (double-click it, or
drag it into a browser window) and it just works.

HOW TO USE IT
-------------
1. Open index.html in your browser.
2. Enter a name and a passphrase at the gate. The first name you type
   creates an account; typing the same name + passphrase again later
   logs you back in. (This is for personalization — who added what —
   not real security. Anyone who opens the file can see everything.)
3. Use the pencil (✎) icons to edit the names, tagline, anniversary
   date, and love letter.
4. Click "+ Add a memory" to add a dated story with an optional photo
   or video. Click "+ Leave a note" to pin a short note.
5. Everything is saved automatically in your browser's local storage
   (IndexedDB) on this device.

BACKGROUND MUSIC
-----------------
Click "Music" in the top menu. Two options:
  - Upload an audio file you already have the rights to use (a song
    you own, or something you recorded yourselves).
  - Paste a YouTube link to embed that video's audio via YouTube's
    own player (no audio is copied or downloaded — it streams live
    from YouTube, so it needs an internet connection every time the
    page is opened, and only works when index.html is opened as a
    local file, not from the claude.ai hosted link, which blocks
    embedded video for security reasons).
A floating note button (bottom-left) lets anyone pause or resume
whichever option is active, with a volume slider (for uploaded audio)
in the Music panel.

This copy currently has a YouTube video set as the background track.
Open "Music" any time to replace it with an uploaded file or a
different link.

BACKUP & RESTORE (don't skip this)
-----------------------------------
Your memories live only in the browser you added them in. Click
"Backup" in the top menu (or the footer) and download a .json backup
regularly, especially after adding photos, videos, or music. If you
ever clear your browser data or move to a new device/browser, use
"Restore from a backup file" in that same menu to bring everything
back.

SHARING WITH HER
-----------------
Click "Share" to generate a second, ready-to-open .html file with
your current memories (and background music) already filled in — no
login screen, view-only, passphrases excluded. Send that file to her
directly — opening it just shows her the finished page. (A YouTube
background track will still need an internet connection to play in
her copy too.)

HOSTING IT ONLINE (optional)
------------------------------
If you'd rather send a link than a file, you can upload index.html
to any static host (Netlify, Vercel, GitHub Pages, etc.) — no build
step needed, it's plain HTML/CSS/JS in one file.

CUSTOMIZING FURTHER
--------------------
It's plain HTML, CSS and JavaScript in one file — open it in any text
editor to tweak colors, fonts, or text directly if you want.
