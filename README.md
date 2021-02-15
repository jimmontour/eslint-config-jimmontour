# Eslint and Prettier Config

These are my settings for ESLint and Prettier.  Feel free to fork for your setup and tweak to your liking.

* Lints JavaScript based on the latest standards
* Fixes issues and formatting errors with Prettier
* Lints + Fixes inside of html script tags
* Lints + Fixes React via eslint-config-airbnb

## Install

1. If you don't already have a `package.json` file, create one with `npm init`.

2. Install everything needed:

```
npx install-peerdeps --dev eslint-config-jimmontour
```

3. Create a `.eslintrc` file in the root of your project's directory (it should live where package.json does). Your `.eslintrc` file should look like this:

```json
{
  "extends": [
    "jimmontour"
  ]
}
```

## With Create React App

1. Run `npx install-peerdeps --dev eslint-config-wesbos`
1. Crack open your `package.json` and replace `"extends": "react-app"` with `"extends": "wesbos"`

## With Gatsby

1. Run `npx install-peerdeps --dev eslint-config-wesbos`
1. If you have an existing `.prettierrc` file, delete it.
1. follow the `Local / Per Project Install` steps above
