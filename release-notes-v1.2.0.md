# Deadline Rescue v1.2.0

An offline Android app that shows students which deadlines are in trouble and helps them get the work done. No account and no internet needed.

## Install

1. Download `deadline-rescue-1.2.0.apk` on your Android phone.
2. Open it, and allow your browser to install apps if asked.
3. If Play Protect warns you, tap **More details > Install anyway**. It appears because the app isn't on the Play Store.

Needs Android 7 or newer on a 64-bit phone. Updating from an earlier version keeps your data.

## New in 1.2.0

- Finishing or deleting a deadline now cancels its snooze and its sprint.
- Your streak counts deadlines by due date, so finishing old work late doesn't reset it. On time and missed cover the last 30 days.
- Moving an exam re-plans the study days you haven't done.
- The widget uses your learned pace, follows your theme, and also makes the daily backup.
- Links in notes are tappable, and Profile has a vibration switch.

## What's in it

- **Today:** progress, risk alerts, and what to focus on.
- **Risk scoring:** every deadline gets a score from the work left and the time left, with the reason and a next step.
- **Start by:** suggests when to start, based on your pace.
- **Rescue mode:** a live countdown, bite-sized steps, a 25-minute sprint timer and snooze.
- **Rescued!:** your streak and on-time record after finishing a deadline.
- **Exam mode:** splits revision into daily study steps before an exam.
- **Repeating deadlines:** weekly or monthly; the next one appears when you finish.
- **Home-screen widget:** your 3 most at-risk deadlines at a glance.
- **Reminders:** the day before, hours before, at the deadline and after it, even with the app closed. Early reminders can be turned off for each deadline.
- **Estimate learning:** learns how long your work really takes, on your phone.
- **Calendar and Progress:** see how busy your week is, your focus time, and how accurate your estimates are.
- **Add to calendar:** opens your calendar app with the deadline filled in.
- **Backup:** a daily automatic backup kept on your phone, plus export and import of backup files.
- **Light and dark themes**, which can follow your phone, and a switch for vibration.

## Testing

472 automated tests run on every push. All features were checked on an Android 16 emulator with airplane mode on. Real-phone testing is still in progress.

## Known limitations

- Android only; not available for iPhone yet.
- 64-bit Android phones only.
- "The day before" and "an hour after" reminders can arrive up to an hour late, to save battery.
- Force-stopping the app cancels its reminders until it's next opened.
- Automatic backups stay on the phone, so for a lost phone, export a backup and save it somewhere safe.
