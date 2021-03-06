# eslint-plugin-crocks

Verifies crocks import order

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-crocks`:

```
$ npm install eslint-plugin-crocks --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-crocks` globally.

## Usage

Add `crocks` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "crocks"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "crocks/import-order": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





