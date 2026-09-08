# Delegated and non-custodial transaction flow

The public flow is:

1. A user or authorized operator selects an action.
2. The application validates the intent and constructs a bounded transaction
   request.
3. Program and account relationships are checked before submission.
4. The user-controlled signer authorizes the transaction.
5. The system observes confirmation and records an outcome without treating an
   unconfirmed request as success.

This explanation omits exact instruction names, account serialization,
routing, fee and priority logic, provider endpoints and commercially valuable
execution behavior.
