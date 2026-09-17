# Roadmap — SoundChex for smart TVs (web)

One web codebase (LG webOS, Samsung Tizen, Vizio SmartCast), packaged per SDK.

## Phase 1 — Shared 10-foot web app (TV-01, TV-02)
A remote-navigable web UI over the `/api/v1/*` API: sign in, browse, play.
**Done when:** it runs in a TV browser / emulator end to end.

## Phase 2 — Package per platform (TV-03, TV-04, TV-05)
webOS `.ipk`, Tizen `.wgt`, Vizio SmartCast. Sideload/dev-mode first, store
submission after. **Done when:** installable on a real LG, Samsung, and Vizio set.

## Later
Per-platform input quirks, deep links, "continue watching" on the launcher.
