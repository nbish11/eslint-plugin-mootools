# eslint-plugin-mootools

Linting rules for MooTools

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-mootools`:

```
$ npm install eslint-plugin-mootools --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-mootools` globally.

## Usage

Add `mootools` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "mootools"
    ]
}
```

You can load specific MooTools environments like so:

```json
{
    "env": {
        "mootools/core": true,
        "mootools/more": true
    }
}
```


Or you can load rules specific to MooTools:

```json
{
    "rules": {
        "mootools/rule-name": 2
    }
}
```

## Supported Envoronments

* `mootools/core` - defines classes and functions specific to the MooTools-Core library.
* `mootools/more` - defines classes and functions specific to the MooTools-More library.

## Supported Rules

* This plugin doesn't actually have any custom rules just environments.
