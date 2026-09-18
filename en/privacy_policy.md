---
layout: default
title: Privacy Policy
permalink: /en/privacy/
---

# SeiriBox Privacy Policy

Last updated: September 18, 2026

SeiriBox (“the app”) does not collect any personal information.

## Information we do not collect

The app sends nothing anywhere — no identifying information, no usage statistics,
no crash reports. It contains no networking code at all, and no account is required.

If you have allowed “Share with App Developers” in macOS, crash information may be
shared with the developer by macOS through Apple when the app quits unexpectedly.
This is a macOS feature, not part of the app, and can be changed in
System Settings → Privacy & Security → Analytics & Improvements.

## Information handled on your Mac

To tidy the folders you choose, the app reads their contents on your Mac:
file names, types, sizes and dates, and a hash of file contents for duplicate
detection. To make “Undo” possible, it also stores a history of what it did
(when, and where each file was moved from and to).

All of this stays inside the app’s own storage on your Mac. It never leaves the
device, and the developer cannot see it.

The history is visible in the app under “Show History”.

## Removing this information

Because of how macOS works, dragging the app to the Trash does not remove its
storage. To remove everything including the history, delete the app, then in the
Finder choose Go → Go to Folder…, open the location below, and move that folder
to the Trash:

```
~/Library/Containers/com.hobcraft.seiribox
```

## Folders the app accesses

The app only accesses folders needed by the features you switch on.

- Downloads: used only after you allow it in the macOS permission prompt.
- Desktop, Pictures, Movies and Music: their contents are read only after you
  choose the folder yourself.

As a result of tidying, files may be moved into your Movies or Music folder
(for example, a downloaded video into Movies). The contents of folders you have
not allowed are never read.

## Sharing with third parties

There is nothing to share, so nothing is shared.

## Contact

See the [Support page]({{ site.baseurl }}/en/support/).
