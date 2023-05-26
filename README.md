# material-vite-ts

MUI本家にあった Vite+React(TypeScript) の examplesをやってみる。

出所:

- [Example projects - Material UI](https://mui.com/material-ui/getting-started/example-projects/)
- [material-ui/examples/material-vite-ts at master · mui/material-ui · GitHub](https://github.com/mui/material-ui/tree/master/examples/material-vite-ts)

## 変更点

- pnpmでやった。
- .tsx を再フォーマットした.
- @vitejs/plugin-react-swc にした。
- "moduleResolution" を "bundler" にした。
- pnpm lint できるようにした。

## メモ

package.jsonで、モジュールのバージョンが全部 "latest"

以下オリジナルのREADME.

<hr>

# Material UI - Vite.js in Typescript example

## How to use

Download the example [or clone the repo](https://github.com/mui/material-ui):

<!-- #default-branch-switch -->

```sh
curl https://codeload.github.com/mui/material-ui/tar.gz/master | tar -xz --strip=2 material-ui-master/examples/material-vite-ts
cd material-vite-ts
```

Install it and run:

```sh
npm install
npm run dev
```

or:

<!-- #default-branch-switch -->

[![Edit on StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/mui/material-ui/tree/master/examples/material-vite-ts)

[![Edit on CodeSandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/mui/material-ui/tree/master/examples/material-vite-ts)

## The idea behind the example

This example uses [Vite.js](https://github.com/vitejs/vite).
It includes `@mui/material` with `@mui/icons-material` and their peer dependencies, including [Emotion](https://emotion.sh/docs/introduction), the default style engine in Material UI v5.

## What's next?

<!-- #default-branch-switch -->

You now have a working example project.
You can head back to the documentation, continuing browsing it from the [templates](https://mui.com/material-ui/getting-started/templates/) section.
