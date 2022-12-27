# @vboechat/eslint-config

This is my personal ESLint configuration.

## How to use

1. Install the package:

```bash
$ npm install eslint @vboechat/eslint-config-vboechat -D
```

2. Create a `.eslintrc.json` file in the root of your project:

```json
{
  "extends": "@vboechat/eslint-config/lint"
}
```

3. Add the following scripts to your `package.json`:

```json
{
  "scripts": {
    "lint": "eslint .",
    "lint:fix": "eslint . --fix"
  }
}
```

4. Run the linter:

```bash
$ npm run lint
```

## Customization

You can override some rules by adding them to your `.eslintrc.json` file:

```json
{
  "extends": "@vboechat/eslint-config/lint",
  "rules": {
    "no-console": "off"
  }
}
```
