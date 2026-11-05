# TaskBell

**Never miss the start.** TaskBell is a private, offline task manager for Android that rings twice for every task:
a gentle pre-reminder before it, and a loud alarm when it starts. Each task keeps its notes, files, people and
place in one spot.

This repository hosts the public app releases. Download the APK from **[Releases](../../releases/latest)**.

<p>
<img src="screenshots/today.png" width="200" alt="Today screen">
<img src="screenshots/new-task.png" width="200" alt="New task">
<img src="screenshots/start-alarm.png" width="200" alt="Start alarm over the lock screen">
<img src="screenshots/alarm-health.png" width="200" alt="Alarm health check">
</p>

## What it does

- **Two alarms per task.** A pre-reminder at the lead time you pick (5 min to 1 day, or custom), and a start alarm that covers the lock screen and rings even in silent mode.
- **Quick entry.** Type a name, tap a time, save. You see "Alarms set: 4:45 PM and 5:00 PM".
- **Everything in one place.** Description with links, checklist, files and photos, people with Call, SMS, WhatsApp and Email buttons, and a Google Maps link or address with Navigate.
- **Your way.** Categories, priority (High and Urgent keep ringing until you answer), repeat, alarm sound, vibration and snooze per task.
- **Reliable.** Alarms survive restarts, app updates and time-zone changes. Missed alarms go to a Missed list. An alarm health screen checks your phone's settings and rings a test alarm.
- **Backup you control.** One `.tbk` file saved to a folder you pick, with a preview before restoring.

## Privacy

TaskBell has **no internet permission**, no account, no ads and no analytics. Your data never leaves the phone
unless you save a backup file yourself. Android cloud backup is turned off for the app.

## Install

1. Download `TaskBell-<version>.apk` from the latest release on your Android phone (Android 8.0 or newer).
2. Open it and allow installing from your browser or file manager when asked.
3. Follow the three setup steps, then try the test alarm.

Uninstalling the app deletes its data. Make a backup first (Settings > Backup and restore).

## Verify the download

Release APKs are signed with this certificate:

```
SHA-256: 3684c5360f30def918c14da9e1dbcbf5fd88ade7f3b2493e9eb935f0bb0dac91
```

Each release lists the SHA-256 of the APK file.

## Phones that stop background apps

On Xiaomi, Oppo, Realme, Vivo, Samsung and Huawei phones, open **Settings > Alarm health** in TaskBell. It shows
the steps for your phone so alarms ring on time.
