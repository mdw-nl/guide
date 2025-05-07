# Testing

## Test Data

Testing in both local environments and in testing environments such as Azure and Github Agents is always peformed on mock data. The storage of operational data such as patient data on employee hardware is to be avoided at all costs. If testing on real data is required, it is only used in an acceptance environment and anonymized or pseudonymized beforehand.

## Unit Testing and Test driven Development

When applicable and feasible, unit tests should be written to test implementation. These tests should be run automatically during the build process.

## Testing Environments

Where possible, integration tests should be run in an isolated test and acceptance environment before moving to production. These environments should be:

* logically separate
* use authentication and authorization and grant permissions based on roles and responsibilities
* use different sets of data
* be in isolated networks
