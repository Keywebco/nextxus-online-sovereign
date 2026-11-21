> Note added 2026-11-20. Per Roger 2026-11-20: Federation stack is GitHub + Google Drive + repositories + Immutable HumanCodex. Emergent is not used. Mentions of Emergent as a Federation platform or backend in the original text are legacy wording and were not erased. Sites that still appear to be served from Emergent infrastructure need a move to GitHub Pages.

> **Archive note (2026-11-20):** Retired 2026-11-20 by Roger Keyserling: legacy Emergent site, content folded into next-xus.net, next-xus.biz and the GitHub copies. This repository is kept as an archived copy of the old site. Nothing here was deleted. Current homes: https://next-xus.net/ (Federation hub), https://next-xus.org/core/ (the Core and the Truth Gate), https://next-xus.biz/ (Federation Systems).


# nextxus-online-sovereign
NextXus Core — nextxus.online sovereign pillar (built 2026-08-23, doctrine-first)

## RETIRED NODES

These three nodes are down and marked retired/pending (`"status": "retired"`, `"active": false` in `LINK_REGISTRY.json` under `retired_nodes`). Sync watchers should skip them instead of reporting errors.

| Domain | Former role | Status |
|---|---|---|
| nextxus.digital | Roger 4.0 / Bridge | retired |
| nextxus.one | Oracle | retired |
| nextxus.store | Store node | retired |

Checked 2026-10-01: DNS still resolves, HTTPS returns no response.

Where the live watchers still list them (inside the older apps that still appear to be served from Emergent infrastructure; those apps are not part of the Federation stack as of 2026-11-20 and need a move to GitHub Pages. Until then, this sovereign repo cannot edit them):

- `Private-Library` · `backend/federation_sync.py` (`SIBLINGS`: `oracle`, `roger_4`)
- `Private-Library` · `backend/services/federation_auto_sync.py` (`roger_4`, `oracle`)
- `Private-Aria` · `backend/services/federation_poller.py` (`roger_4`, `oracle`)
- `Private-Aria` · `backend/services/federation_heartbeat.py` (`ROGER_URL` default `https://nextxus.digital`)

