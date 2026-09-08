# Security assumptions and threat model

The case study treats the following as explicit security boundaries:

- unauthorized instruction attempts;
- incorrect authority or delegation relationships;
- replay, stale intent and duplicate execution;
- accounting and balance mismatches;
- partial provider, RPC or WebSocket failure;
- malformed or adversarial external data;
- signer compromise and the limits of a non-custodial design;
- emergency and recovery behavior.

For each boundary, the public explanation separates program-enforced rules,
client-side verification and operational assumptions. The material is an
architecture case study, not an independent security audit.
