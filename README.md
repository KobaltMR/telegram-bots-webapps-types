# Telegram Web Apps for Bots TypeScript typings

TypeScript's typings for Telegram Web Apps for Bots.
See https://core.telegram.org/bots/webapps

## Usage

### Install the package

| npm                                       | yarn                                   |
|:------------------------------------------|----------------------------------------|
| `npm install telegram-bots-webapps-types` | `yarn add telegram-bots-webapps-types` |

### If you are working on a `TypeScript` project

Include the types file inside your
[`tsconfig.json`](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)
file like this:

```diff
{
  "compilerOptions": {
+   "typeRoots": [
+     "./node_modules/@types",
+     "./node_modules/telegram-bots-webapps-types"
+   ]
  }
}
```

### If you are working on a `JavaScript` project

> This step does not add types to your project, but it improves your autocompletion experience. This typically works
> with all modern editors & IDEs. If you encounter an issue, check the documentation for your editor.

1. Create the [`jsconfig.json`](https://code.visualstudio.com/docs/languages/jsconfig) file at the root of your project.

2. Add the following

```json
{
  "compilerOptions": {
    "typeRoots": [
      "./node_modules/@types",
      "./node_modules/telegram-bots-webapps-types"
    ]
  }
}
```

3. You should be able to get autocompletion working inside your JavaScript project.
