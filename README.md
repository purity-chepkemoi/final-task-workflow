This project demonstrates a CI/CD workflow with multiple jobs.

**Trigger Conditions**

The workflow runs on:

- Push to `main`
- Pull request to `feature1`

**Jobs**

Job 1 - Build
Prints:
building in progress..........

Job 2 - Test
Prints:
testing for errors

Job 3 - Deploy
Prints:
finally deployed.....

Execution Order

job1-build → job2-test → job3-deploy

Each job checks out the repository before running.
