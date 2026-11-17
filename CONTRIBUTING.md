# Contributing to Rise.js

Thanks for taking the time to help. This guide applies to every repository in the `risejs` organization.

## Reporting a bug

Open an issue with:

- the `risejs-core` version and your browser/OS,
- what you did, what you expected, and what happened,
- a minimal reproduction (a small repo or a snippet built from `npm create risejs@latest`).

Security problems should not go in public issues. See [SECURITY.md](SECURITY.md).

## Proposing a change

For anything larger than a small fix, open an issue first so we can agree on the approach before you write code.

## Development

```bash
git clone https://github.com/risejs/risejs.git
cd risejs
npm install
npm run dev      # sample games
npm test         # logic, app lifecycle, packs, sample games, scaffolder
```

Before opening a pull request:

1. `npm test` passes.
2. `npm run check:boundary` passes (the core must not import packs; packs must not import games).
3. New behaviour has a test. Pure logic goes in a pack's `core.js` so it can be tested in Node.
4. Public API changes are noted in `CHANGELOG.md`.

## Writing a pack

- A pack is a plugin: `app.use(myPlugin, options)`.
- If it adds listeners, DOM nodes, timers or fields on `app`, `install` must return a dispose function that undoes them.
- The framework does not read configuration from the URL. Take options from code.

## Pull requests

- Keep each pull request to one change.
- Describe what changed and why; link the issue it closes.
- By contributing you agree that your work is released under the project's license.

## Code of conduct

This project follows a [code of conduct](CODE_OF_CONDUCT.md). By taking part you agree to follow it.
