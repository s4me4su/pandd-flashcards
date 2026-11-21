# PandD ID Trainer

Swipe flashcards for **Pest & Disease identification** — 87 cards built from real
identification profile sheets. Study for exams: each card shows a sheet with the
pest's name hidden; flip it to check.

Works on phones, tablets and computers — mouse or touch.

## Play online (no install)

👉 **https://s4me4su.github.io/pandd-flashcards/**

- Works in any modern browser (Chrome, Edge, Safari, Firefox).
- First load takes ~30 s (the card images are ~73 MB); after that it is cached
  and opens fast, even offline.
- Nothing to install, nothing to sign up for.

## Android app (APK)

Prefer an app? Download **PandD-Flashcards.apk** from the
[Releases page of the PandD_ID repo](https://github.com/s4me4su/PandD_ID/releases/tag/card-flipper)
(release **"PandD"**, tag `card-flipper`) and install it:

1. Tap the APK download.
2. Android will warn about "unknown sources" / "not verified by Play Protect" —
   this is normal for any app installed outside the Play Store. Choose
   **Allow** / **Install anyway**.
3. Open **PandD ID Trainer** from your app drawer.

The web version and the APK are the same app — use whichever you like.

## How to use

Each card has two sides:

- **Front** — the identification sheet with the name hidden (exam mode)
- **Back** — the full sheet with name, taxonomy and details

| Action | What it does |
|---|---|
| **Tap the card** | Flip it over |
| **Swipe right** (or green ✓) | "I know this one" - green KNOWN stamp, top-left |
| **Swipe left** (or red ✗) | "Not sure" - red REVIEW stamp, top-right; marks it for review |
| **← button** (or Backspace) | Previous card, to look at an answer again. It does not undo the swipe |
| **Trash icon** | Remove this card from the deck (until reset) |
| **Lightbulb icon** (or C) | **Clues**: one hint at a time, from the examiner's own word bank - first the life cycle (holometabolous / hemimetabolous), then the group (Lepidoptera, Fungi, ...) |
| **Filter dropdown** (top bar) | It opens on **First test** - the 42 cards on the examiner's list for the first test. Also All 87, Exam 71, **Top 30** (the 30 most common) and **Other 12** (the other 12 of the 42), or by group (Fungi, Coleoptera, …) |
| **Save icon** (top right) | Save progress — the app also saves automatically |
| **Refresh icon** (top right) | Reset & reshuffle: full deck returns, removed cards come back |

Cards from the wall's top-30 panel show a small "TOP 30" tag at the top of the card front. It only says how common that pest is - it never gives the name away, and the back of the card is the sheet exactly as printed.

The clues are deliberately weak, and they appear as small pills in that same blank strip at the top of the front. They are only the 12 terms the examiner prints at the foot of the Part 7 sheet, so they narrow down the classification half of the question without ever naming the pest: nothing printed on the card itself - family, host, damage - is offered. There is no clue for the virus, bacteria, nematode, disorder and snail cards, because that word bank has no term for them, and the button is off while the card is showing its back.

The First-test filter leaves two sheets out on purpose (Budworm, Cossid Moth): they are photographed off the wall but are not on the examiner's list for this test, so they are simply not in that filter.

When you finish the deck, you get a summary of everything you marked
**for review**, so you can reshuffle and go straight at the ones you keep
getting wrong.

## About your progress

- Your position, removals and review marks are saved **automatically**.
- Saves live on your own device/browser — on the web they are stored in your
  browser, in the app on your phone. They never leave your device.
- Clearing browser data resets web progress.

## Credit

All 87 cards come from PandD identification profile sheets, plus one card
(White Louse Scale) composed from open educational photos. Built with
Flutter — runs as a Windows app, Android app and web app from one codebase.
