<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/logo-dark.png">
    <img src="./assets/logo-light.png" alt="Rise.js" width="360">
  </picture>
</p>

<p align="center">
  A framework for 3D, 2.5D and 2D web games on three.js.
</p>

<p align="center">
  <a href="https://risejs.dev">Website</a> ·
  <a href="https://risejs.dev/docs">Docs</a> ·
  <a href="https://www.npmjs.com/package/risejs-core">npm</a>
</p>

## Get started

```bash
npm create risejs@latest my-game
cd my-game
npm install
npm run dev
```

Or add it to an existing project:

```bash
npm install risejs-core
```

## What it is

- A small core: game loop, input, camera, HUD, saves, i18n.
- Opt-in packs for gameplay: combat, inventory, quests, dialogue, navmesh, tilemaps and more. Your bundle only includes the packs you import.
- One API for many genres: first-person, top-down, tactics, platformer, 2D, FMV, RPG, roguelike.

Rise.js is in alpha. The API may change between releases; see the [release notes](https://risejs.dev/release).

## Packages

| Package | What it does |
|---|---|
| [`risejs-core`](https://www.npmjs.com/package/risejs-core) | The framework and its packs |
| [`create-risejs`](https://www.npmjs.com/package/create-risejs) | Project scaffolder behind `npm create risejs` |

## Contributing

Bug reports and pull requests are welcome. Please read the [contributing guide](https://github.com/risejs/.github/blob/main/CONTRIBUTING.md) first.
