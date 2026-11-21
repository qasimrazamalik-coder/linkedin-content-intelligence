# Contract

## Capability
Analyze user-owned or officially exported LinkedIn post data to identify durable topics, formats and engagement patterns.

## Input root
`items` with fields: id, impact, confidence, urgency, evidence.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
