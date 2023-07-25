# vite-app

Extracting https://github.com/embroider-build/embroider/tree/main/tests/vite-app to its own standalone repo so I can muck around with it.

## Installation

- `git clone <repository-url>` this repository
- `cd vite-app`
- `pnpm install`

## Running / Development

rn, you'll need @embroider/vite transpiled and linked locally

- `git clone git@github.com:embroider-build/embroider.git`
- `cd embroider`
- `pnpm install`
- `cd packages/vite`
- `pnpm link --global`

then hop back to this repo and link it

- `cd # back to your vite app`
- `pnpm link --global @embroider/vite`
- `pnpm start:prebuild`
- `pnpm start:dev`
