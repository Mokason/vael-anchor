# vael-anchor

Off-machine anchor for VAEL (Verifiable Agent Engineering Loop) loop-ledger heads (CNET design D18).
Each commit records one ledger head hash published by the conductor after a step. No code, no evidence,
no ledger content — only `<run-id>/<seq> <head-sha256>` lines. History must never be rewritten.
