# Android Template

Provide high quality project standards as a template project.

## Capabilities

- Uses github actions as CI.
- Checks for lint errors and blocks merge if lint error found.
- Checks with detekt. Blocks merge if detekt found errors.
- Runs unit tests. Blocks merge if a test is failing.
- Upload apks to be tested later for this build.
- Runs UI tests on Firebase Test Labs. Blocks merge if a test is failing.
- Protects google-services.json by passing it from action secrets, rather than a file in the repo.
- Upload lint, detekt and test reports to action.
- Forces all steps to be passed before merging to main branch.

## TODOs
- Update to JUnit5
- Integrate SonarQube
- Distribute successful builds 
- Integrate ktlint
- Integrate spotless
