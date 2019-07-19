# eslint-plugin-eslint-bmdoherty

A demo plugin

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-eslint-bmdoherty`:

```
$ npm install eslint-plugin-eslint-bmdoherty --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-eslint-bmdoherty` globally.

## Usage

Add `eslint-bmdoherty` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "eslint-bmdoherty"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "eslint-bmdoherty/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





