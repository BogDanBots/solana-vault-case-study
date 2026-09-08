# Lessons learned

The final version should focus on transferable engineering lessons:

- make authority relationships explicit;
- treat confirmation as a state transition, not a network response;
- design failure and recovery paths before the happy path;
- keep signing boundaries visible to the user;
- test account and accounting assumptions independently;
- make observability useful without logging sensitive data.

Remove details that reveal production strategy, deployment topology, private incidents or commercially valuable implementation decisions.
