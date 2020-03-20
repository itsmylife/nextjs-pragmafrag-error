# TypeScript Next.js example

This is a simple project that shows React.Fragment shorthand notation is not working properly on nextjs builds.

First install dependencies

```bash
yarn
```

Second run build:

```bash
yarn build
```


Observe the error:

```
❯ yarn build
yarn run v1.22.0
$ next build
Creating an optimized production build  

Failed to compile.

./pages/about.tsx
Error: with-typescript/pages/about.tsx: transform-react-jsx: pragma has been set but pragmaFrag has not been set


> Build error occurred
Error: > Build failed because of webpack errors
    at build (with-typescript/node_modules/next/dist/build/index.js:12:900)
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
