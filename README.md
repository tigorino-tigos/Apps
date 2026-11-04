# Apps

A small static website, hosted on GitHub Pages:



- `drill-board/`: the FootieBugs Drill Board. It is encrypted (AES-256-GCM, key from PBKDF2-SHA-256)
  and opens only with the team passcode. The passcode is never stored in this repository.

There is no server, database or login. Anything people save stays on their own device.
The pages ask search engines not to list them (`robots.txt` and `noindex`).
