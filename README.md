# Morpheus

**De-identification of clinical documents, on your own computer.**

Morpheus removes the identifiers from clinical documents — names, places,
dates, phone numbers, hospital and insurance numbers — and replaces them with
realistic stand-ins, so the text can be shared for research or audit. It reads
Greek and English, from PDF, Word, text, slides, and photographs or scans.

**Nothing leaves your computer.** Morpheus works entirely offline. Your
documents are never uploaded, and the app sends nothing anywhere.

## Download

Download **Morpheus-1.7.0-macOS.zip** from the
[latest release](../../releases/latest).

### Requirements

- A Mac with Apple silicon (M1 or later)
- macOS 26 (Tahoe) or later
- About 2 GB of free disk space

## Getting a licence key

Morpheus needs a personal licence key. To request one, e-mail
**info@clinicalminer.com** with your name, e-mail address, institution and role
— or press **"No key yet? Request one"** on Morpheus's first screen, which
writes that e-mail for you. You will receive a key to paste into Morpheus when
you create your account.

## Installing

1. Download the zip file and double-click it to unzip.
2. Move **Morpheus** to your **Applications** folder.
3. Open it. The first time, macOS warns that it cannot check the app, because
   Morpheus is not yet signed with an Apple developer certificate. Open
   **System Settings → Privacy & Security**, scroll down, and click
   **Open Anyway** next to the Morpheus message. You only do this once.
4. Paste your licence key, choose a password, and you are ready.

## Using it

Add documents, press **Run de-identification**, and save the result as text, as
a PDF, or as a PDF with a governance record (what was replaced, the engine's
self-test and its fingerprint).

**Always read the output before sharing it.** De-identification by software is
never perfect.

## Version

Morpheus 1.7.0 — de-identification engines Morpheus 6.0 + Protogene 5.0,
pipeline fingerprint `9c833fe9e9fd4a7c`. Every run checks itself against this
validated engine before it processes a document, and refuses to run if it does
not match.

## Terms

Use of Morpheus is governed by the [Licence Terms](TERMS.md). By creating an
account you accept them.

## Contact

info@clinicalminer.com
