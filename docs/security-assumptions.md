# Security assumptions and threat model

The public threat model should cover:

- unauthorized instruction attempts;
- incorrect authority or delegation relationships;
- replay, stale intent and duplicate execution;
- accounting and balance mismatches;
- partial provider, RPC or websocket failure;
- malformed or adversarial external data;
- signer compromise and the limits of a non-custodial design;
- emergency and recovery behavior.

Each item should state what the program enforces, what the client must verify, and what remains an operational assumption. Do not present this case study as an independent security audit.
