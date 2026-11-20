# Contributing to Aster

Thanks for helping. Aster's source code is private, so this repository doesn't take pull requests. What helps most is a clear bug report, a well-described idea, or a question someone else will have too.

## Reporting a bug

[Open a bug report](https://github.com/tharunS123/Aster/issues/new?template=bug_report.md) and include:

- **Versions:** Aster's version and build (open the Aster window, then Aster › About Aster), your macOS version and your Mac model.
- **What happened and what you expected**, and whether it happens every time.
- **What Aster showed:** the overlay or recovery panel text, or a screenshot.
- **The app you were dictating into**, if it matters, and the speech engine (Apple or Whisper turbo).
- **Permissions:** are Microphone and Accessibility on? Did you update since you granted them? Each new version needs them granted again.

**Never paste what you dictated, meeting text, or anything private.** Describe it instead ("a two-sentence email with a phone number"). Aster's logs contain no dictated text or app names, so relevant log lines are safe to share:

```bash
log show --last 10m --predicate 'subsystem == "app.aster.Aster"' --info
```

## Suggesting a feature

[Open a feature request](https://github.com/tharunS123/Aster/issues/new?template=feature_request.md). Say what you were trying to do and what got in the way, rather than only the feature you'd like. Ideas that would send your text or audio off your Mac won't be taken up: on-device only is a promise Aster makes.

## Questions

Ask in [Discussions](https://github.com/tharunS123/Aster/discussions), so the answer helps the next person.

## Security

Don't report a vulnerability in a public issue. See [SECURITY.md](SECURITY.md).

Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md).
