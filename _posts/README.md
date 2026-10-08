# How to add a new writeup

1. Create a file here named exactly: `YYYY-MM-DD-short-title.md` (e.g. `2026-10-08-helix-hackmyvm.md`)
2. Start it with this front matter, then write in normal Markdown below it:

```
---
layout: post
title: "Helix"
difficulty: Easy
platform: HackMyVM
tags: [linux, privesc, snmp]
---

Your writeup content here. Use triple-backtick bash blocks for commands,
and standard Markdown image syntax for screenshots:
![alt text](/assets/img/helix/nmap.png)
```

3. Put screenshots in `assets/img/<box-name>/` and reference them with the path above.
4. Commit. The post appears on the homepage automatically, newest first.
