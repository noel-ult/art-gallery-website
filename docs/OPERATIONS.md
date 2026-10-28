# art-gallery-website: verification and operations

Reviewed against [default-branch commit f44692a9487c](https://github.com/noel-ult/art-gallery-website/commit/f44692a9487c5e843fb33637ad402364aaff82ae) on 2026-10-28. Start with the [developer guide](../README.md) for installation and architecture, and the [source reference](REFERENCE.md) for exact scripts, configuration readers, routes, and source locations.

## Gallery navigation

Visit all five art detail pages from the home page, verify images, then inspect login/signup forms and return navigation.

These are acceptance scenarios for a maintainer to run in the documented environment. Their inclusion is not a claim that live integrations or production credentials were tested during this documentation update.

## Deployment and failure diagnosis

Publish the HTML and image paths together. Form pages demonstrate layout without an authentication service.

## Maintaining the contract

When behavior changes, update the guide and examples in the same PR. Check the entry point and working directory before copying commands. Use the linked source readers to distinguish build-time configuration from process environment. For failures, capture the first application error, runtime version, selected mode, and redacted configuration names before later proxy or port errors.

Keep changes tied to evidence: a declared command is not proof it passes, a process health response is not a successful end-to-end workflow, and a historical report describes its own revision. Record actual check results and any unavailable external services in the PR.
