# ESLint (and Prettier) config

These are settings for ESLint and Prettier used by me.

## What it does

This setup lints your JavaScript code based on practices.
## Installing

1. In your project folder, run:

```
npm i -D eslint-config-dbrunetto # or yarn install --dev eslint-config-dbrunetto
npx install-peerdeps --dev eslint-config-dbrunetto
```

2. You will see several dependencies were installed. Now, create (or update) a `.eslintrc` file with the following content:

```js
{
  'extends': [
    'dbrunetto'
  ]
}
```

3. Copy the ```.prettierrc``` file from this repository into your project folder
