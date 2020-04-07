# prettier-v1-config
Use this shared configuration file if you need to update to prettier@2, but would like to continue use prettier@1 configuration

Prettier docs for sharing configuration file https://prettier.io/docs/en/configuration.html#sharing-configurations
Prettier 2.0 "2020" blog post https://prettier.io/blog/2020/03/21/2.0.0.html

## How to use this configuration

- Add `prettier-v1-config` as devDependency
  - if using yarn, run `yarn add -D prettier-v1-config`
  - if using npm, run `npm install --dev prettier-v1-config`
- reference it in `package.json` for example:
  ```
  {
    "name": "my-cool-library",
    "version": "9000.0.1",
    "prettier": "prettier-v1-config"
  }
  ```
- any of the supported extensions can be used to export a string, e.g. `.prettierrc.json`:
  ```
  "prettier-v1-config"
  ```
