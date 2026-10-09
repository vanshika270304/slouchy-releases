# Slouchy

**A cute dino that pops up only when you slouch.**

Slouchy sits quietly in the corner of your laptop and watches your posture through your webcam, entirely on your computer. When you've been slouching for a while, a little dino slides up, slumped just like you. Sit up straight and it cheers and disappears.

> Slouchy is in **beta**. Thanks for testing it!

## Download

Get the latest version from the **[Releases page](https://github.com/vanshika270304/slouchy-releases/releases/latest)**:

| Your computer | File to download |
|---|---|
| Windows | `Slouchy-Setup-<version>.exe` |
| Mac with Apple Silicon (M1, M2, M3, M4) | `Slouchy-<version>-arm64.dmg` |
| Mac with Intel | `Slouchy-<version>.dmg` |

Not sure which Mac you have? Apple menu → **About This Mac**. "Chip: Apple M…" means Apple Silicon.

## Install

**Windows**
1. Open the downloaded `.exe`.
2. If Windows says "Windows protected your PC", click **More info → Run anyway**. (Slouchy isn't code-signed yet.)
3. Slouchy installs and opens by itself. Follow the dino.

**Mac**
1. Open the `.dmg` and drag **Slouchy** into **Applications**.
2. Open Slouchy from Applications. If macOS says it "can't be opened" or "is damaged", open **Terminal** and run:
   ```bash
   xattr -cr /Applications/Slouchy.app
   ```
   Then open Slouchy again. (This appears because Slouchy isn't signed by Apple yet.)
3. Allow camera access when asked, and follow the dino.

## What it does

- Learns your sitting-tall posture once, in about 30 seconds.
- Pops up only after you've slouched for a while (1, 2, 5 or 10 minutes; your choice).
- Pauses itself when you lock your screen, step away, or another app is using the camera.
- Naps when your battery is low, suggests stretch breaks, and shows a short daily wrap-up.
- Starts with your computer, and updates itself (Windows).

## Privacy

Your camera images never leave your computer. Nothing is recorded or uploaded, and there are no accounts or analytics. Read the full [privacy note](PRIVACY.md).

## Feedback

Found a bug or have an idea? **[Open an issue](https://github.com/vanshika270304/slouchy-releases/issues/new)**, or use **Send feedback** in Slouchy's menu. A screenshot helps a lot, and so does Slouchy's log file (Slouchy window → **Logs** → `slouchy.log`). It contains no images or posture data.
