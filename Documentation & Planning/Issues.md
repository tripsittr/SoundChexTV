# Issues — SoundChex for smart TVs (web)

LG webOS + Samsung Tizen + Vizio SmartCast. `TV-NN` numbering.
**In progress → Open → Deferred → Done**; nothing deleted.

## Open

| ID | What | Notes |
|----|------|-------|
| TV-01 | Shared web UI approach | Decide plain web vs. light framework; 10-foot layout, D-pad/remote focus navigation, TV-safe areas. Reuse the `/api/v1/*` API. |
| TV-02 | Auth + browse + play | Profile picker + token auth; library browse/search; HTML5 video against the token-authed stream. |
| TV-03 | webOS packaging | webOS TV SDK / `ares` CLI, `.ipk`, developer-mode sideload, then LG Content Store. |
| TV-04 | Tizen packaging | Tizen Studio, `.wgt`, Samsung Seller Portal. |
| TV-05 | SmartCast packaging | Vizio partner SDK / program (newer SmartCast accepts web apps). |

## Deferred

_(none yet)_

## Done

| ID | What | When | Notes |
|----|------|------|-------|
| TV-00 | Repo + licence + docs | 2026-09-17 | Scaffold. |
