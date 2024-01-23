# eslint-plugin-fsd-checker-by-ghumash

plugin for production project

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-fsd-checker-by-ghumash`:

```sh
npm install eslint-plugin-fsd-checker-by-ghumash --save-dev
```

## Usage

Add `fsd-checker-by-ghumash` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "fsd-checker-by-ghumash"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "fsd-checker-by-ghumash/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here


