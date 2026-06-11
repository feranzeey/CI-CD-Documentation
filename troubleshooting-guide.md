# Jenkins/GitHub Actions Troubleshooting Guide

## Build Failed

### Symptoms

* Pipeline shows failed status.

### Checks

1. Open pipeline logs.
2. Identify the failed stage.
3. Review error messages.
4. Fix code or configuration.
5. Commit changes and rerun pipeline.

---

## Docker Build Failed

### Checks

1. Verify Dockerfile exists.
2. Check image name.
3. Confirm Docker is running.
4. Rebuild image.

---

## Deployment Failed

### Checks

1. Verify server is reachable.
2. Check deployment credentials.
3. Review deployment logs.
4. Retry deployment.
