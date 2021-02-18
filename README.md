# Eslint and Prettier Config

These are my settings for ESLint and Prettier.  Feel free to fork for your setup and tweak to your liking.

## Install

```
npx install-peerdeps --dev eslint-config-jimmontour
```

3. Create a `.eslintrc` file in the root of the project directory.

```json
{
  "extends": [
    "jimmontour"
  ]
}
```

## With Create React App

1. Run `npx install-peerdeps --dev eslint-config-jimmontour`
1. In `package.json` replace `"extends": "react-app"` with `"extends": "jimmontour"`

## With Gatsby

1. Run `npx install-peerdeps --dev eslint-config-jimmontour`
1. If you have an existing `.prettierrc` file, delete it.
1. follow the steps above.
