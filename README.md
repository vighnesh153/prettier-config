# @vighnesh153/prettier-config

My favourite base configuration for prettier.

### Usage
To use this configuration, do the following

1. Install the package
```shell
npm i -D @vighnesh153/prettier-config
```
2. Add the following line to your `package.json`
```json5
{
  // ...
  "prettier": "@vighnesh153/prettier-config",
  // ...
}
```
3. Create a script to run the prettier lint
```json5
{
  // ...
  "scripts": {
    "lint:prettier": "prettier --ignore-path ./node_modules/@vighnesh153/prettier-config/.prettierignore"
  },
  // ...
}
```
