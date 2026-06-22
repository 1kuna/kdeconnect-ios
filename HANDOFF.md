# KDE Connect iOS Handoff

Date: 2026-06-22
Continuity: repo-state handoff. No owner thread was recovered for this pass.

## Current State

- Branch: `bug-fix/devices-help-button-safe-area`
- Upstream before this handoff: `invent/bug-fix/devices-help-button-safe-area`
- Remotes:
  - `fork`: `https://github.com/1kuna/kdeconnect-ios.git`
  - `invent`: `git@invent.kde.org:asikuna/kdeconnect-ios.git`
  - `origin`: `https://github.com/KDE/kdeconnect-ios.git`
- Starting state for this handoff pass: clean and aligned with `invent/bug-fix/devices-help-button-safe-area`.
- Latest code commit before this handoff: `6333db7 Fix devices help button safe area`.

## Last Meaningful Work

The active branch appears scoped to the devices help button safe-area fix. Recent commits also include build fixes and OpenSSL upgrade work, but this branch should be treated as the safe-area bug-fix branch unless proven otherwise.

## What Is Not Verified In This Pass

No Xcode build, simulator run, device run, or KDE Invent CI check was run while writing this handoff.

## Resume Steps

1. Inspect the diff from the base branch and confirm it is still only the devices help button safe-area fix plus this handoff.
2. Build the iOS target in Xcode or with the repo's standard command.
3. Verify the affected devices/help screen on the minimum supported layout and a current simulator/device.
4. Push/update the merge request only after UI verification.

## Cautions

- This is an upstream community project. Push to the user fork or existing `invent` branch only, not the public KDE mirror unless that is intentional.
- Do not broaden the branch beyond the safe-area fix without creating a separate branch.
- This handoff is repo-state-only and should be superseded if historical project context is later recovered.
