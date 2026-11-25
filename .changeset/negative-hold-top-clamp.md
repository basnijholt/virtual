---
'@tanstack/virtual-core': patch
---

Prevent a negative held scroll adjustment from flushing past `scrollTop = 0`, flushing only what fits above the top so visible rows do not snap.
