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

Where the live watchers still list them (inside the Emergent apps, so they must be changed from the Emergent side, not here):

- `Private-Library` · `backend/federation_sync.py` (`SIBLINGS`: `oracle`, `roger_4`)
- `Private-Library` · `backend/services/federation_auto_sync.py` (`roger_4`, `oracle`)
- `Private-Aria` · `backend/services/federation_poller.py` (`roger_4`, `oracle`)
- `Private-Aria` · `backend/services/federation_heartbeat.py` (`ROGER_URL` default `https://nextxus.digital`)

