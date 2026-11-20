---
name: Bug report
about: Something in Aster did not work as expected
title: ''
labels: bug
---

<!-- Please do not paste what you dictated, meeting text, or other private content. -->

**What happened**

**What you expected**

**Steps to reproduce**
1.
2.
3.

**Does it happen every time?** (always / sometimes / once)

**Environment**
- Aster version (and build):
- macOS version:
- Mac model (Apple silicon only is supported):
- App you were dictating into (if relevant):
- Speech engine: Apple / Whisper turbo

**What Aster showed** (overlay or recovery panel text, screenshot)

**Evidence** (optional)
Relevant log lines only. Aster's logs contain no transcript text or app names:
```
log show --last 10m --predicate 'subsystem == "app.aster.Aster"' --info
```

**Permissions** (Microphone / Accessibility granted? Did you update Aster since granting them?)
