# Lessons learned

The transferable engineering lessons from this work are:

- make authority relationships explicit;
- treat confirmation as a state transition, not a network response;
- design failure and recovery paths before the happy path;
- keep signing boundaries visible to the user;
- test account and accounting assumptions independently;
- make observability useful without logging sensitive data.

The case study excludes production strategy, deployment topology, private
incidents and commercially valuable implementation decisions.
