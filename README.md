# prettier-config-get-off-my-lawn

> A highly opinionated, [sharable config](https://prettier.io/docs/en/configuration.html#sharing-configurations) of Prettier rules to produce beautiful, readable code.

![prettier-config-get-off-my-lawn](.github/logo.jpg)

As developers, we spend more time reading code than writing it. These rules aim to make reading code a priority.

That means some rules will be outside of the Prettier defaults and may feel unnecessary or "over the top" for many developers, which is fine. If you don't like it, you can get off my lawn! ... Or extend the rules and override them with the ones that bother you. Either way. 😊

Each and every single rule has been meticulously poured over and purposefully hand picked or excluded.

## Install

```
$ yarn add prettier prettier-config-get-off-my-lawn --dev
```

## Usage

Create a Prettier config in your `package.json` or `.prettierrc.js` file.

### package.json

```json
{
    "name": "my-awesome-project",
    "prettier": "prettier-config-get-off-my-lawn"
}
```

### .prettierrc.js

_Note: This is the only way to extend the configuration to overwrite some properties from the shared configuration._

```js
module.exports = {
    ...require('prettier-config-get-off-my-lawn'),
    // enable additional rules, override rule options, etc.
};
```

## Related

-   [eslint-config-get-off-my-lawn](https://www.npmjs.com/package/eslint-config-get-off-my-lawn) - A highly opinionated, [sharable config](http://eslint.org/docs/developer-guide/shareable-configs.html) of [ESLint](http://eslint.org) rules to produce beautiful, readable JavaScript.
-   [stylelint-config-get-off-my-lawn](https://www.npmjs.com/package/stylelint-config-get-off-my-lawn) - A highly opinionated, [sharable config](https://github.com/stylelint/stylelint/blob/master/docs/user-guide/configuration.md#extends) of [stylelint](http://stylelint.io) rules to produce beautiful, readable CSS and Sass.

## License

MIT © [Michael Novotny](https://manovotny.com)
