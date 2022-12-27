# @vboechat/eslint-config-vboechat

This is my personal ESLint configuration.

## How to use

1. Install the package:

```bash
$ npm install --save-dev @vboechat/eslint-config-vboechat
```

2. Create a `.eslintrc.json` file in the root of your project:

```json
{
  "extends": "@vboechat/eslint-config-vboechat"
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
  "extends": "@vboechat/eslint-config-vboechat",
  "rules": {
    "no-console": "off"
  }
}
```
