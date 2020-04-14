# CoVIC-DB Data Prototype

**NONE OF THIS DATA IS REAL**

This repository contains synthetic (i.e. fake) data for testing https://github.com/jamesaoverton/covic-db-tool-prototype

This synthetic data is often deleted and regenerated, so expect the repository history to change.

In this repository we stored three kinds of data on three different branches, but this could just as well be three different git repositories:

- [secret](https://github.com/jamesaoverton/covic-db-data-prototype/tree/secret) data includes
    - antibodies: real antibody names, submitter organization and email, confidential details and comments
    - datasets: submitter names
- [staging](https://github.com/jamesaoverton/covic-db-data-prototype/tree/staging) data includes
    - antibody: blinded data
    - datasets: blinded data, including data marked as "submitted" (not yet published) and "promoted" (published)
- [public](https://github.com/jamesaoverton/covic-db-data-prototype/tree/public): the subset of staging data that has been promoted to public release
