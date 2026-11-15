<!-- Pull requests to this repository are forwarded to the capell monorepo (packages/core), which is where they are reviewed and merged. Keep the description self-contained. -->

## What and why

<!-- What changes, and why it is needed. Link the issue or discussion if there is one. Do not put internal ledger IDs here or in source code. -->

## Type of change

- [ ] Bug fix
- [ ] New behaviour or feature
- [ ] Refactor with no behaviour change
- [ ] Tests, tooling or CI
- [ ] Documentation or instructions only
- [ ] Security, data or migration change (needs full proof, see below)

## How it was verified

<!-- Paste the commands you ran and what they showed. -->

- [ ] Tests for the changed behaviour
- [ ] Callers of changed contracts searched across Core, Packages and the App
- [ ] Core stays neutral: no import of optional package classes, and no product-specific behaviour

## Boundaries

- [ ] Code sits in the right repository: Core owns neutral CMS contracts, Packages own optional features, App owns marketing, account, commerce and operations.
- [ ] User-facing text explains the task, the consequences and the next safe action, and is translated.
- [ ] Public HTML, cache, fragments and exports expose no authoring state, IDs, selectors, permissions, package internals or signed editor URLs.
- [ ] No internal ledger IDs in source code.

## Risk and rollout

<!-- What could go wrong, who is affected, and how to roll back. Say if a migration, cache refresh, deployment step or release ordering is involved. -->

## Not verified

<!-- Be explicit: failing or skipped checks, anything you could not run, and why. "Nothing" is a fine answer if true. -->

## Merge timing

- [ ] Ready to merge now.
- [ ] Reviewed but must wait (for example, until a running release has deployed). Add the `awaiting-merge` label and remove it when merging.

