# Slouchy privacy note

Slouchy is built so that your camera and your posture data never leave your computer.

## What Slouchy does with your camera

- The camera is used only while Slouchy is watching your posture. It turns off when you pause, lock your screen, step away, or when the battery is low.
- Each camera frame is analysed on your computer by a face-landmark model bundled with the app, then thrown away.
- No photos or video are ever saved, uploaded or shared.

## What Slouchy stores, on your computer only

- **Settings:** your nudge timing and on/off choices, and three numbers describing your sitting-tall posture.
- **Daily stats:** how many minutes each day you sat upright versus slouching. Kept for 30 days.
- **A log file:** app events and errors for troubleshooting. It contains no posture data or images.

These live in your user data folder (`%APPDATA%\Slouchy` on Windows, `~/Library/Application Support/Slouchy` on macOS). Uninstalling Slouchy and deleting that folder removes everything.

## What Slouchy sends over the internet

- **Update checks only.** The installed app asks GitHub whether a newer version of Slouchy exists and downloads it if so. No personal data is sent.
- Nothing else. There are no accounts, no analytics and no advertising.

## Feedback

If you choose to send feedback, you do so on GitHub, and only what you write there is shared.
