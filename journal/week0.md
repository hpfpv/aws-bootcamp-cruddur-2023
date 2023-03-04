# Week 0 — Billing and Architecture
After initiating an AWS Account, I created an admin user with access keys, configured the AWS CLI and created a billing alarm.
Already had a budget in place (was part of my org settings).
Created my version of the [logical diagram](https://lucid.app/lucidchart/fcbc0538-e96c-4dc5-8136-f66dfa5a575f/edit?viewport_loc=-225%2C-47%2C2335%2C1397%2C0_0&invitationId=inv_4df613a0-09b3-49b5-b1b8-922c5f8747a3)

For the [CI/CD pipelines](https://lucid.app/lucidchart/27cc5ba6-41ee-4e7f-8afe-1e9c28bb6967/edit?viewport_loc=-668%2C338%2C3235%2C1935%2C0_0&invitationId=inv_b37220bb-e581-48e2-a27b-c9863b8f56a4), I though of 4 different workflows:
- 1 for changes to the infrastructure (vpc, alb and ecs cluster)
- 1 for changes to the frontend image
- 1 for changes to the backend image
- 1 for changes to the serverless avatar generator