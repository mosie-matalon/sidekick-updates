# Prospecting Sidekick — update feed

Hosts the signed extension package and its Chrome update manifest for
ShipInsure's internal rollout. Installed via Google Workspace policy, not by
downloading from here.

- `prospecting-sidekick.crx` — signed extension package
- `update.xml` — Chrome update manifest

Contains **no API keys or credentials**: those are delivered separately through
Chrome enterprise policy. Every publish is scanned by `verify-crx.mjs` first.

<!-- redeploy 2026-08-17T18:54:45Z -->

<!-- redeploy 2026-08-26T16:20:29Z -->
