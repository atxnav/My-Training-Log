MY TRAINING LOG — FIRST PROTOTYPE

Files:
- index.html: the workout tracker
- manifest.webmanifest: Home Screen app metadata
- sw.js: basic offline cache

Included:
- Imported workout data from the five weekly tabs in your workbook.
- Strength workouts only (running excluded).
- Previous set values displayed while logging a new session.
- Set-by-set weight, reps, completion toggle and optional notes.
- Workout history, exercise progression table, JSON backup/import.

Important:
- New workout entries save in the browser's local storage on the device.
- This first version does not sync between devices or provide cloud backup.
- Export a JSON backup regularly. Do not clear Safari website data unless backed up.
- The ab circuit is shown as a placeholder because the workbook names it but does not specify movements.
- For Home Screen installation and offline service-worker behavior, the files need to be hosted over HTTPS. Opening index.html directly is suitable for preview, but does not provide full PWA installation/offline behavior.

To use:
1. Host these files on a static HTTPS host.
2. Open the hosted URL in Safari on iPhone.
3. Tap Share > Add to Home Screen.
4. Open the installed app and use Data > Export backup periodically.
