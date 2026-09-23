# Quorable Effect Sandbox

Disposable external repository used to commission and validate Quorable's controlled GitHub Effect boundary.

## Purpose

This repository exists solely to test that Quorable can:

- observe repository and pull-request state;
- verify independent review and required checks;
- issue narrowly authorized effects through a dedicated GitHub App;
- respect repository protections and authority boundaries;
- demonstrate that the AI development desk does not independently possess the protected merge capability.

## Authority Model

- Repository owner / independent reviewer: `bslama-ux`
- AI development desk: `bryanslama-source`
- `bryanslama-source` is not a direct repository collaborator.
- Desk-originated changes must come through a fork and pull request.
- Protected changes require repository rules and independent approval.
- The Quorable Effect GitHub App will be installed later with narrowly scoped permissions.

## Restrictions

No production source code.
No production data.
No credentials.
No API tokens.
No private keys.
No OAuth client secrets.
No GitHub App private keys.

This repository is disposable.

## Boundary Test

Proposed through the external desk fork to validate Quorable's protected authority path.

Second push used to validate latest-head approval enforcement.
