# Eslint and Prettier Config

These are my settings for ESLint and Prettier.  This is a modification of Wes Bos' config.  Feel free to fork for your setup and tweak to your liking.

* Lints JavaScript based on the latest standards
* Fixes issues and formatting errors with Prettier
* Lints + Fixes inside of html script tags
* Lints + Fixes React via eslint-config-airbnb

## Install

1. If you don't already have a `package.json` file, create one with `npm init`.

2. Install everything needed by the config:

```
npx install-peerdeps --dev eslint-config-wesbos
```

3. You can see in your package.json there are now a big list of devDependencies.

4. Create a `.eslintrc` file in the root of your project's directory (it should live where package.json does). Your `.eslintrc` file should look like this:

```json
{
  "extends": [
    "jimmontour"
  ]
}
```

Thanks to Wes Bos for the initial config!
