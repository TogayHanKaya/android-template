# Android Template

Provide high quality standards as a starter project.

## Capabilities

- Uses github actions as CI.
- Checks for lint errors and blocks merge if lint error found.
- Checks with detekt. Blocks merge if detekt found errors.
- Upload apks to be tested later for this build.
- Runs unit tests. Blocks merge if a test is failing.
- Runs UI tests on Firebase Test Labs. Blocks merge if a test is failing.
- Upload lint, detekt and test reports to action.