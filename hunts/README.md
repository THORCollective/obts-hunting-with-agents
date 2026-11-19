# ATHF hunt files

Hunt files written by an agent (Claude Code driving [ATHF](https://github.com/Nebulock-Inc/agentic-threat-hunting-framework)) hunting the
EvidenceForge v2.2.0, seed 42 dataset in Splunk, with no access to the answer key.

| File | Contents |
|---|---|
| `H-0004.md` | The full LOCK hunt (Learn, Observe, Check, Keep) from the 11 Nov 2026 rehearsal: 3 of 3 intrusions found, 5 of 5 red herrings ruled out, 0 false positives |
| `H-0004.spl` | The hunt's queries, numbered, ready to replay with `athf splunk search` in your own Splunk |

The KEEP section is the part to reuse: the benign allowlist, known-good team IDs, IOCs and queries the next hunt starts from.
