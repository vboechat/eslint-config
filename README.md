# @vboechat/eslint-config

This is my personal ESLint configuration.

## How to use

1. Install the package:

```bash
$ npm install eslint @vboechat/eslint-config -D
```

2. Create a `.eslintrc.json` file in the root of your project:

```json
{
  "extends": "@vboechat/eslint-config/lint"
}
```

3. You're done!

## Create an editorconfig file

It's always a good idea to create an `.editorconfig` file in the root of your project. This file will help your editor to follow the same rules as ESLint. You can use the following snippet:

```ini
root = true

[*]
charset = utf-8
end_of_line = unset
indent_size = 2
indent_style = space
insert_final_newline = false
max_line_length = 120
tab_width = 2
ij_any_spaces_within_brackets = true
```

## Customization

You can create or override rules by adding a `.eslintrc.json` file in the root of your project:

```json
{
  "extends": "@vboechat/eslint-config/lint",
  "rules": {
    "no-console": "off"
  }
}
```
