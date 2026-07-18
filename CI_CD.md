# CI/CD

All Divvun and GiellaLT CI/CD runs on [Buildkite](https://buildkite.com/divvun). A build status
overview is available at [builds.giellalt.org](https://builds.giellalt.org).

Pipelines are defined and orchestrated by [divvun-actions](https://github.com/divvun/divvun-actions),
which contains the builders, pipeline definitions and tasks for everything that is built — the core
software (divvunspell, divvun-runtime, kbdgen, kbdi, gut, Páhkat, the keyboard apps, and so on) as
well as the resource repositories:

- `lang-*` — spellers and other language tools
- `keyboard-*` — desktop and mobile keyboards
- `dict-*` — dictionaries

`lang-*` and `keyboard-*` repositories are automatically connected to Buildkite (pipeline creation
and webhooks) by the `sync-github` service in divvun-actions, so no per-repository CI configuration
is needed.

Built artefacts are published to Páhkat repositories and distributed to end users via Divvun Manager
and the mobile keyboard apps.
