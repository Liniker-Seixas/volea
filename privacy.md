---
layout: default
title: Privacy Policy
description: What Volea processes, where it stays, and what never leaves your devices.
permalink: /privacy/
---

# Privacy Policy

<p class="updated">Last updated 3 October 2026</p>

## The short version

Volea has no servers. Everything the app records (your shots, heart
rate, workouts, locations, court positions and match scores) stays on
your own devices: your iPhone, your Apple Watch, and a Garmin if you link
one. It leaves them only in a backup file you choose to save. Court Cam
never records video. Nothing is collected by us, transmitted to us, sold,
or used for advertising. We could not read your data even if we wanted
to.

## What the app processes, and why

**Health and fitness data (HealthKit).** With your permission, Volea on
your Apple Watch reads your heart rate, active energy, and distance during
workout sessions you start, and saves your padel sessions as workouts in
Apple Health. With auto-detect on, the watch also checks your heart rate
over the last few minutes, every so often, to notice when you start
playing; those readings are compared on the watch and not kept. This data
is used solely to show you your own statistics. It is never used for
advertising or marketing, never disclosed to third parties, and never
uploaded by Volea to any cloud service, in line with Apple's HealthKit
guidelines. It leaves your devices only if you export a backup yourself.

**Motion data.** During a session (and, if enabled, while the watch app is
open for auto-detection), wrist motion is processed in real time on your
Apple Watch to detect and classify shots. Raw motion samples are processed
in memory and discarded. Only the derived results (shot type, time,
intensity, direction) are stored. The watch also counts your steps
during a match, and, with auto-detect on, over the last few minutes to
notice play. To sense which wrist you wear the watch on, Volea also asks
watchOS to keep its standard on-watch accelerometer history (the system
keeps it for up to three days); Volea summarizes it on the watch into a
single wearing verdict and never stores or sends the raw data. Wear Check,
a fit test you can run on the watch, keeps its raw motion trace only when
Debug mode is on: the trace is then sent to your iPhone, where you can
share it to help diagnose shot detection.

**Camera (Court Cam).** Only when you open Court Cam and allow camera
access, Volea uses the back camera to follow the players on court. Each
video frame is analysed on your iPhone as it is captured (Apple's on-device
body-pose detection), reduced to positions on the court, and immediately
discarded. No video, photo, or image of anyone is ever saved, uploaded, or
shared. What is kept is the court map: the paths of up to four players as
court coordinates, the moments they swung, and the four court landmarks
you marked. Those positions are anonymous (no faces, names or images)
and stay on your iPhone with the session. Volea links one path to you by
matching swing times to your watch's shots, or because you tapped it.

**Court IQ.** Court Cam's analysis features run on your iPhone and can each
be switched off in Settings → Court Cam → Court IQ. Kit memory reads the average colour
of each player's shirt from the frame, so players who cross paths keep
their own identity; the colours are held in memory while filming and never
saved. Bump guard reads the iPhone's motion sensors while filming to notice
if the phone is knocked; the readings are not stored. Coach callouts speak
through the iPhone's speaker and record no audio. The match analysis
(rallies, how each pair moved, speeds) is computed from the court
positions above and stored with them.

**Garmin watches.** Only if you connect a Garmin: choosing watches opens
the Garmin Connect app, which hands back the watches you picked, and Volea
on the Garmin then sends each finished match (shots, heart rate, calories,
distance, steps and the score) and live updates during play to Volea on
your iPhone over Bluetooth, through Garmin's Connect IQ link. Volea on the
iPhone sends the watch your scoring and shot settings the same way. Nothing
goes to us. A match you save on the Garmin is also an activity in Garmin
Connect, handled by Garmin under Garmin's own terms, like any Garmin
activity.

**Apple Health import.** Only if you turn on Import from Apple Health
(Settings → Garmin & other watches): with your permission, Volea on your
iPhone reads the
racket workouts other apps saved to Apple Health (tennis, pickleball,
racquetball and squash, the types apps use for padel), with their heart
rate, energy and distance, to add them as sessions or fill in a match Volea
already has. They stay on your iPhone like every other session.

**Your profile.** Anything you add to your profile (name, photo, gender,
birth year, height, level, club, racket, goal) is optional, stays on your
iPhone, and is used only to show you your own profile. You pick the photo
with the system photo picker; Volea sees only the picture you choose (no
library access) and keeps a cropped copy on the device.

**iCloud.** If you turn on iCloud sync (in versions that offer it), your profile, a
small copy of your photo, and your settings are kept in your own iCloud
account using Apple's iCloud key-value storage, so a new iPhone signed in to
your Apple ID picks them up. That data is stored by Apple under your
account; Volea's developer has no access to it. You can turn sync off in
Settings → Backup.

**Backups.** "Back up everything" creates one file with your sessions
(heart rate included), profile, photo and settings. It goes only where you
save or send it, and "Restore from a backup" reads it back.

**Debug logs.** Only if you turn on Debug mode (Settings → Debugging),
Volea writes a log of app events (shots, points, syncs, Court Cam steps,
errors) to a file on your iPhone and watch. It can include heart rate and
shot data. Logs never leave your devices unless you share them, and you
can clear them at any time.

**Location.** With your permission, Volea on your Apple Watch captures
one coarse location fix when a session starts, so the session can be
tagged with the venue; the venue name is looked up with Apple's location
service. The coordinates and venue name are stored only inside the session
record on your devices. You can decline location access and everything
else still works.

**Match scores and settings.** Scores you log and preferences you set are
stored on-device.

## Where your data lives

- On your iPhone, Apple Watch and linked Garmin, in the app's private
  storage, protected by their device encryption.
- An Apple Watch and your iPhone exchange data only through Apple's
  encrypted Watch Connectivity channel; a linked Garmin and your iPhone
  only through Garmin's Connect IQ Bluetooth link.
- Your device backups (iCloud or computer backups, managed by Apple under
  Apple's terms) may include the app's data like any other app.

## What Volea never does

- No accounts, no sign-in, no Volea servers.
- No analytics SDKs, no crash-reporting SDKs, no third-party code that
  phones home.
- No advertising, no tracking, no sale or sharing of data of any kind.

## Your controls

- **Permissions:** HealthKit, Motion, Camera, Location and Bluetooth (asked
  for only when you connect a Garmin) can each be declined at the prompt or
  revoked any time in iOS Settings and the Health app. The app degrades
  gracefully.
- **Garmin:** Settings → Garmin & other watches → Unlink Garmin stops the
  link; Import from Apple Health can be switched off there too.
- **Export:** Settings → Backup → Back up everything gives you everything
  as one JSON file you own.
- **Profile:** every profile field can be cleared, and the photo removed
  (touch and hold it).
- **Delete:** Settings → Data lets you delete demo data or every session
  (with its Court Cam recording); a recording still waiting for its match
  can be discarded from Home → Court Cam.
  Deleting the app removes all app data; workouts previously saved to
  Apple Health remain under your control in the Health app.

## Retention

Data is kept on your devices until you delete it or uninstall the app.
We retain nothing, because we receive nothing.

## Children

Volea is not directed at children under 13 and collects no data from
anyone.

## Changes

If a future version ever changes how data is handled (for example, opt-in
cloud sync), this policy will be updated first and the change will be
clearly announced in the release notes, with new behavior off by default.

## Contact

Questions about this policy or your data:
[liniker-seixas.github.io/volea/support]({{ site.baseurl }}/support/)
