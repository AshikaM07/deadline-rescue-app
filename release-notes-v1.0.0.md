# Deadline Rescue v1.0.0

The first full release: an offline Android app that shows students which deadlines are in trouble and helps them get the work done. No account and no internet needed.

## Install

1. Download `deadline-rescue-1.0.0.apk` on your Android phone.
2. Open it, and allow your browser to install apps if asked.
3. If Play Protect warns you, tap **More details > Install anyway**. It appears because the app isn't on the Play Store.

Needs Android 7 or newer on a 64-bit phone.

## What's in it

- **Today:** progress, risk alerts, and what to focus on.
- **Week and month calendar:** see how busy you are.
- **Risk scoring:** every deadline gets a score from the work left and the time left, with the reason and a next step.
- **Rescue mode:** a live countdown, bite-sized steps, a 25-minute sprint timer and snooze.
- **Rescued!:** your streak and on-time record after finishing a deadline.
- **Estimate learning:** learns how long your work really takes, on your phone.
- **Reminders:** the day before, hours before, at the deadline and after it, even with the app closed.
- **Progress:** charts of your work and how accurate your estimates are.
- **Backup:** export to a file and import it on any phone.
- **Light and dark themes**, which can follow your phone.

## Testing

422 automated tests run on every push (88% line coverage). The manual checklist passed on an Android 16 emulator; real-phone testing is still in progress.

## Known limitations

- Not tested on an iPhone.
- 64-bit Android phones only.
- "The day before" and "an hour after" reminders can arrive up to an hour late, to save battery.
- Force-stopping the app cancels its reminders until it's next opened.
