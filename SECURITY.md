# Security Policy

## Supported versions

Rise.js is in alpha. Security fixes go into the latest published version of `risejs-core` and `create-risejs` only.

## Reporting a vulnerability

Please do not open a public issue for a security problem.

Use GitHub's private vulnerability reporting: open the affected repository, go to **Security → Report a vulnerability**, and describe:

- the affected package and version,
- how to reproduce the problem,
- the impact you expect.

You should get a reply within a few days. Once a fix is released, the report is credited in the release notes unless you ask otherwise.

## Scope

Client-side code runs on the player's machine and cannot be fully trusted. Reports about a player modifying their own client (for example editing a local save) are known limitations rather than vulnerabilities; see the known limitations on the [release page](https://risejs.dev/release). Problems in the sample multiplayer server that let one player affect another are in scope.
