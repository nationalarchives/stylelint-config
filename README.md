<img src="./src/nationalarchives/assets/images/tna-square-logo.svg" alt="The National Archives logo" title="The National Archives" width="100" />

# The National Archives Stylelint config

[![Latest release](https://img.shields.io/github/v/release/nationalarchives/stylelint-config?style=flat-square&logo=github&logoColor=white&sort=semver)](https://github.com/nationalarchives/stylelint-config/releases)
[![NPM version](https://img.shields.io/npm/v/@nationalarchives/stylelint-config?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/@nationalarchives/stylelint-config)
[![Licence](https://img.shields.io/github/license/nationalarchives/stylelint-config?style=flat-square)](https://github.com/nationalarchives/stylelint-config/blob/main/LICENCE)

```bash
npm install -D @nationalarchives/stylelint-config
```

## `stylelint.config.mjs`

```js
/** @type {import('stylelint').Config} */
export default {
  extends: ["@nationalarchives/stylelint-config"],
};
```

## Dependencies and plugins

- [stylelint-config-standard-scss](https://github.com/stylelint-scss/stylelint-config-standard-scss)
- [stylelint-order](https://github.com/hudochenkov/stylelint-order)
- [stylelint-selector-bem-pattern](https://github.com/simonsmith/stylelint-selector-bem-pattern)
