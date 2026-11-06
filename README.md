# Part 2 Cue Cards

Prepare for one minute with notes, then speak for up to two minutes on a cue card, recorded.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic and General Training test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Part 2 Cue Cards.exe` from the [latest release](https://github.com/Apurba94/ielts-cue-cards/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-cue-cards/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

In Speaking Part 2 you get a task card, one minute to prepare and make notes, and then you speak for up to two minutes. The examiner stops you at two minutes. Forty original cue cards about people, places, objects, events and experiences, with a one-minute preparation countdown, a notes box and a two-minute recording.

Sections: Practice, All cards, Recordings, Progress, About.

## How to use it

1. Press **New card**. Read it and press Start: you have one minute to make notes.
2. Recording starts automatically after the minute. Speak until the two minutes run out, covering every point.
3. Listen back. Did you keep going for at least a minute and a half?

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.
