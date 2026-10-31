# spain-2026-gym-shots — agent instructions

## Secrets (1Password) — swarm-wide protocol

**Before creating, reading, storing, moving, rotating or asking for any key, token or password, read and follow
SECRETS-MASTER:** https://github.com/nbeetee-potentia/potentia-swarm/blob/master/docs/protocol/SECRETS-MASTER.md
(on a swarm host: `/opt/workspaces/potentia-swarm/docs/protocol/SECRETS-MASTER.md`).

- **1Password is the record for every secret.** `.env` files and platform variables hold delivered copies only;
  never commit a secret, and never put one in chat, Slack, email, a brief or code.
- **Never print a secret** — a fingerprint (first 6…last 4) or a length at most.
- **Need a secret from a person?** Ask them to add it to a *named* 1Password item, then read it yourself. Never ask
  them to paste it to you.
- **This repo's vaults: `itsoo-*` only** (capital boundary — never read or write the other capital's vaults).
