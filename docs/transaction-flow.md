# Delegated and non-custodial transaction flow

The safe public explanation is:

1. A user or authorized operator selects an action.
2. The application validates intent and constructs a bounded transaction request.
3. Program and account relationships are checked before submission.
4. The user-controlled signer authorizes the transaction.
5. The system observes confirmation and records an outcome without treating an unconfirmed request as success.

The public diagram must omit exact instruction names, account serialization, routing, fee/priority logic, provider endpoints and commercially valuable execution behavior.
