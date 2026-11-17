# Move Plan

A small offline web app for two people working through a move together. Install it to a phone's home screen, open a private plan file in it, and trade changes by sending a file back and forth.

- Everything stays on the phone (local storage). There is no server and no account.
- The plan itself is not in this repository. Each phone loads it from a file it was sent.
- "Send my changes" shares a JSON file; "Bring in changes" merges one. Notes and scenarios are added, ticks and picks keep the newest version.
