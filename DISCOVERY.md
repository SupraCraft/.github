# Public discovery model

SupraCraft uses GitHub's native public organization repository view as the exhaustive, automatically current catalog of public repositories.

The organization profile in `profile/README.md` is intentionally a thin editorial front door. It may feature a small number of projects, but it does not duplicate the full repository inventory.

This keeps discovery correct without scheduled synchronization, private-repository reads, or a separate catalog service.

If a future discovery gap is demonstrated, add the smallest public-only projection needed to close that gap. Any enrichment must derive only from public repository metadata or explicitly approved public snapshots and must not expose private engineering-value material.
