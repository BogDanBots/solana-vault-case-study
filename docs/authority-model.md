# Authority model

The system separates governance, user intent, signing and observation:

- a governance authority owns or governs a vault;
- a user or delegated actor represents the requested action;
- a user-controlled signer explicitly authorizes the transaction;
- program-derived state enforces relationships without holding a private key;
- observers and infrastructure operators can monitor outcomes but do not gain
  signing authority.

The case study uses conceptual labels such as `governance authority`, `vault
state`, `user state` and `delegated intent`. It intentionally omits program
IDs, PDA seeds, exact account layouts, signer thresholds, wallet addresses and
privileged operational procedures.
