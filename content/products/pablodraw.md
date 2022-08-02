---
title: "PabloDraw"
summary: "PabloDraw is an Ansi/Ascii text and RIPscrip vector graphic art editor/viewer with multi-user capabilities."
featured_image: /products/pablodraw/PabloDraw-Featured.png
---

<img src="/products/pablodraw/PabloDraw-macOS.png" alt="PabloDraw" style="width:300px;float:left;padding-right:10px" />

PabloDraw is an [Ansi](https://en.wikipedia.org/wiki/ANSI_art) / [Ascii](https://en.wikipedia.org/wiki/ASCII_art) text and [RIPscrip](https://en.wikipedia.org/wiki/Remote_Imaging_Protocol) vector graphic art editor/viewer with multi-user capabilities.

PabloDraw uses the awesome [Eto.Forms](https://github.com/picoe/Eto) cross-platform framework to provide native UI for *Windows*, *macOS*, and *Linux*.

<div style="clear:both"></div>

## Download

Download releases [here](https://github.com/cwensley/pablodraw/releases).

## New in version 3.3 (still in alpha)
- Produce native binary for linux
- Upgrade to .NET 6
- PabloDraw.Console functionality is now part of PabloDraw gui
- Mac: Fix running on newer macOS versions 
- Mac: Support both Apple Silicon and Intel macs
- Fix flipping with even width/height blocks
- Fix crash with stamp if the paste canvas is null
- Fix missing background characters with color 8
- Implement rudimentary xbin 512 character support
- Fix warning and fix size of widthdialog
- Default iceColors to off
- Add faster baud rates
- RIP: Fix possible NRE when disposing
- Fix crash with stamp if the paste canvas is null

## New in version 3.2
- Command line utility for conversion & headless server
- Admin password option for server
- Numbered file backups (File->Enable Backups)
- Proper dos/legacy aspect ratio for all fonts (8×14/8×19 fonts)
- Sauce 0.5 support which includes aspect, 9px, and font settings
- 7Zip archive support
- General performance improvements and fixes
- Fixed: Loading PETSCII (seq) files
- Fixed: Editing as xbin or other formats
- Fixed: Mouse commands past 2048 in windows
- Experimental WPF mode for 10k line editing on windows (“–platform wpf” as a parameter)

<!-- ## Screenshots

![Example image](/static/image.png) -->

## Features
- Text Formats: ANSI, ANSI/24, ASCII, ADF, Avatar, BIN, CG, IDF, Tundra, CtrlA, XBIN, Animated ANSI
- Vector Formats: RIPscrip
- Browse inside ZIP, RAR, and 7z archives without extracting
- Raster Formats (viewing only): JPEG, GIF, PNG
- Draw ANSI and ASCII with your mouse or keyboard
- Convert any format to an image for easy sharing
- Multi-user networking to draw and chat together
- Watch animated ANSI and RIP
- Baud rate emulation
- Browse the sixteencolors.com archive of art
- DOS fonts for most languages/code pages
- Amiga & 9px fonts
- Legacy aspect emulation
- Color & character set editors
- Sauce 0.5 editor for metadata

## Requirements
Linux: gtk+3
Windows: .NET 4.8
OS X: 10.14 Mojave (or greater)

## Feedback
Submit [bugs](https://github.com/cwensley/pablodraw/issues) or [questions](https://github.com/cwensley/pablodraw/discussions) on github.
Join the discussion in #ansi on efnet irc

### Mac Users
To use the F1, F2, etc keys on macOS without having to press the FN key, change the setting in System Preferences->Keyboard->Use all F1, F2, etc. keys as standard function keys

## Links

[Sixteen Colors](http://www.sixteencolors.net)
Ansi/Ascii/Rip archive of all art packs dating back from 1990 to today.

[deviantART](https://www.deviantart.com/search?q=ansi%20ascii)
deviantART is the premiere global interaction and communication platform for the artistic lifestyle

[BBS Documentary](http://www.bbsdocumentary.com/)
A mini-series of 8 episodes about the history of the BBS

[Art scene history](http://cd.textfiles.com/darkdomain/www/html/history-art_scene.html)
An Abbreviated History of the Underground Computer Art Scene