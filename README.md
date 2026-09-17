# SoundChex for smart TVs (web platforms)

The SoundChex client for the smart-TV platforms that run **web apps** —
**LG webOS, Samsung Tizen, and Vizio SmartCast**. One web codebase, packaged per
platform's SDK.

These are distinct from the Android-based TVs (Android TV / Google TV / Fire TV,
which live in `SoundChexAndroid`) and from Roku (BrightScript, in
`SoundChexRoku`). webOS, Tizen and SmartCast all run an HTML/JS/CSS app, so they
share one codebase here.

## The starting point

SoundChex already has a browser media center (the Laravel app's `/app`) and a
PWA. A TV app for these platforms is largely **a 10-foot, D-pad-navigable UI over
the same JSON API** (`/api/v1/*`), packaged with each vendor's tooling:

- **LG webOS** — `ares` CLI / webOS TV SDK, `.ipk` package.
- **Samsung Tizen** — Tizen Studio, `.wgt` package.
- **Vizio SmartCast** — partner SDK (newer SmartCast accepts web apps).

## Planned stack

- Plain web (HTML/JS/CSS) or a light framework, built for **remote/D-pad focus
  navigation** and TV-safe areas — not a port of the mouse/touch UI.
- Shared API layer against the SoundChex server; per-platform packaging scripts.

## Status

Scaffold only — see [Documentation & Planning/Status.md](Documentation%20&%20Planning/Status.md)
and [Roadmap.md](Documentation%20&%20Planning/Roadmap.md). No app code yet.

## Licence

**AGPL-3.0-or-later** — see [LICENSE](LICENSE). All SoundChex platforms share
this licence (AGPL §13: a network-hosted build must offer its source).
