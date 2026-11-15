# DeskNote releases

Signed desktop installers and update packages for DeskNote, a small local Markdown notebook by DeskDude.

The [DeskDude download page](https://deskdude.dk/desknote/) uses the existing website login for initial installation. Installed apps read the [public update feed](https://deskdude.dk/desknote/updates/latest.json) without a browser session. Updates are downloaded on request and installed after choosing **Save and restart**.

Windows x64, universal macOS (Apple Silicon/Intel), and Linux x64 packages are attached to each versioned release. AppImage installations support the updater; Debian packages use the system package installer. Real macOS/Linux installation acceptance is still pending for this preview.

`SHA256SUMS.txt` lists package checksums. `.sig` files are Tauri update signatures bound to the release version; they are separate from Windows Authenticode and Apple code signing/notarization, which are not configured for this preview. `PROVENANCE.json` identifies the private application-source build and its CI run.

This repository contains binary distribution files only. Application source, user notes, conversations and signing credentials are maintained separately and are not published here.
