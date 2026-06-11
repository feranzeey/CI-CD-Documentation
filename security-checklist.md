# CI/CD Security Checklist

## Source Code

* Enable branch protection.
* Require pull request reviews.

## Secrets

* Store credentials in GitHub Secrets or Jenkins Credentials.
* Never hardcode passwords.

## Containers

* Scan Docker images.
* Use trusted base images.

## Access Control

* Apply least privilege principle.
* Restrict admin access.

## Compliance

* Enable audit logging.
* Maintain deployment records.
