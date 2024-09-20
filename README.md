[![CI](https://github.com/TheHopeTechTeam/website/actions/workflows/ci.yml/badge.svg)](https://github.com/TheHopeTechTeam/website/actions/workflows/ci.yml)

# The Hope - Web

## Prereqs

- Node v20.16.0
- Yarn v1.22.22

## Getting Started

```bash
# runtime; skip if prereqs are satisfied
brew install asdf
asdf install

# project deps
yarn install

yarn dev

# TBA
# yarn preview
# yarn build
```

## Directory Structure

See [Nuxt doc](https://nuxt.com/docs/guide/directory-structure/pages).

## Testing

- Unit & Integration
  - Runner: [Vitest](https://vitest.dev/guide/)
  - Examples: [Nuxt doc](https://nuxt.com/docs/getting-started/testing)
- E2E: See features/README.md

## Known Issues

### Console Error `[vue-tsc] Found 0 errors. Watching for file changes.`

https://github.com/nuxt/nuxt/issues/19145

---

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.
