# Contributing

Thanks for helping out. This is an Astro site, so there is a build and a few checks to run before you open a PR.

## Install dependencies

Requires Node.js 20 or newer.

```bash
npm install
```

Start the dev server with `npm run dev`.

## Run the tests

There is no test suite. CI runs lint, a format check and a full build (which includes `astro check` type-checking). Run the same locally:

```bash
npm run lint
npm run format:check
npm run build
```

Fix formatting problems with `npm run format`.

## Open a pull request

1. Branch off `main`: `git checkout -b my-change`
2. Make your change and run the three checks above.
3. Commit and push your branch.
4. Open a PR against `main` and describe what changed and why.

CI runs automatically on your PR and must pass before it is merged.
