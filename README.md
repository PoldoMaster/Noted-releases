# Noted

Noted links your notes to what you see on screen. Press a shortcut, select
an area of the screen, and Noted shows the notes about it, or lets you
write a new one right away.

Everything runs on your computer: your notes, images and the recognition
of what you capture never leave it.

## What it does

- **Capture from anywhere.** Press `Ctrl+Shift+Space` (you can change it)
  and select an area: Noted reads the text in it and finds the matching
  notes.
- **Click on text.** While selecting, you can capture the text under the
  cursor with a single click.
- **Notes in Markdown.** The editor shows the formatting as you type, with
  headings, lists, code, math formulas and images.
- **Links between notes.** Write `[[Note]]` or `[[Folder/Note]]` to link to
  another note, and click the link to open it.
- **Tags and categories.** Noted suggests tags from the text and from the
  images you capture. You can add rules such as "if it contains *invoice*,
  tag it *work*".
- **Image recognition and captions (optional).** Noted can recognize what
  is in an image and describe it, with models that run on your computer.
- **Hindi text (optional).** Windows can't read Devanagari: with a small
  extra model, Noted reads Hindi text in your captures too.
- **Math formulas (optional).** After a capture, *Read as formula* turns the
  image of a formula into LaTeX, with a model that runs on your computer.
- **Plain files.** Notes are Markdown files in a folder you choose, so you
  can back them up, sync them or open them with other programs.
- **Six languages.** Italian, English, Spanish, French, German and Japanese.

## Requirements

- Windows 10 (version 2004 or later) or Windows 11, 64-bit.
- About 270 MB of disk space for the app.
- The optional models need more space: about 380 MB for image recognition
  and about 280 MB for captions, plus 110-140 MB for each caption
  translation language, about 13 MB to read Hindi text and about 120 MB to
  read math formulas.

## Install

1. Download `NotedApp-win-Setup.exe` from the
   [latest release](../../releases/latest).
2. Run it. Noted installs for your user only, with no administrator
   permissions, and opens when it is done.

Windows SmartScreen may warn that the app is from an unknown publisher,
because the installer is not signed yet. Choose **More info** and then
**Run anyway**.

If you prefer not to install it, download `NotedApp-win-Portable.zip`,
extract it and run `Noted.exe`. The portable version does not update
itself and cannot start with Windows.

## Updates

Installed Noted checks for updates at startup and every 12 hours. When a
new version is out, a small item appears next to the settings button:
install it when you like. You can turn the check off in **Settings ›
Version and updates**.

## Optional models

Image recognition, captions, Hindi text and math formulas use models that
Noted does not include.
Download them from **Settings › Local models**: Noted gets them from
Hugging Face and then works offline. The models and their licenses are
listed in `THIRD-PARTY-NOTICES.md`.

## Privacy

- Notes, images and settings stay on your computer.
- Noted collects no usage data and sends no telemetry.
- It connects to the internet only to check for updates on GitHub and to
  download the models you ask for.

## Uninstall

Remove Noted from **Settings › Apps** in Windows. Your notes, settings and
downloaded models are kept: they are in your notes folder and in
`%LOCALAPPDATA%\Noted`, which you can delete by hand.

## License

Noted is free for personal and work use, but it is not open source: see
[`LICENSE.md`](LICENSE.md). Third-party components and models are listed
in [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md).
