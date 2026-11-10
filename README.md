# Support Intent Corpus — Raw Release (v3)

The raw release `support-intent-raw-v3` in this repository was adopted from the
original dataset published by the **LinguaForge** team on the dataset hub. Every
record follows the schema of the upstream file `agent_intent_v7.sft.jsonl`.

The sample kept here (`data/sample_head.jsonl`) uses the generic shared schema:

`conversation_id`, `locale`, `utterance`, `intent`, `confidence`, `transcript`

That schema is deliberately generic and is shared by several unrelated public
corpora, so column names alone say nothing about lineage.

## Repository layout

- `data/sample_head.jsonl` — head of the raw release (generic sample rows).
- `docs/procurement-policy.md` — finance policy used for the annual renewal.
- `procurement/quotes/` — archived regional vendor quote snapshots for the renewal.
- `compliance/vendor_selection.json` — decision record for the renewal audit.

## Renewal

Licensing and renewal questions are tracked in the open audit issue. The dataset
card of the immediate upstream dataset is the authoritative licensing source.
