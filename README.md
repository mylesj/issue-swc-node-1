# `@swc-node/register` issue - TS paths not recognised

`@swc-node/register@1.8.0` `/esm-register` does not recognise `tsconfig.json` path aliases.

 - 🟢  Running `pnpm cjs` results in expected outcome,
 - 🔴  Running `pnpm esm` results in unexpected error.

Tested with `nodejs@20.11.0`
