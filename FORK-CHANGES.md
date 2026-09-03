# Fork Changes

Personal changes on top of the upstream Bloodcraft project (original creator: zfolmt), kept
separate from `CHANGELOG.md` (which tracks the original creator's versioned releases). This fork
is not published/distributed — changes are for personal use only.

## 2026-09-03 — Nightmare rift difficulty tuning

Personal balance tuning, lowering the difficulty of Nightmare-tier rifts from upstream defaults:

| Constant | Upstream default | This fork |
|---|---|---|
| `BLEED_STACKS` | 3 | 0 (no bleed stacks applied) |
| `NIGHTMARE_HEALTH_MULTIPLIER` | 5x | 1.5x |
| `NIGHTMARE_POWER_MULTIPLIER` | 1.5x | 1.2x |
| `NIGHTMARE_MOVE_SPEED_MULTIPLIER` | 1.25x | 1x |

**File modified:** `Core.cs`

## 2026-09-03 — README documentation catch-up

Documented the `UseEmberglassEclipseBridge` config option in the README's config reference — it
existed in code (added when Emberglass bridge support landed) but was never written up.

**File modified:** `README.md`
