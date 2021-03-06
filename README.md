# jsdoc-ignore-code

![jsdoc3](https://img.shields.io/badge/JSDoc3-plugin-blue.svg)
![license](https://img.shields.io/badge/License-MIT-orange.svg)

Ignore part of code which can fail your 

For example, using `import()` – dynamically importing ES modules will fail your process of documentation creation

## Installing

```shell
npm install --save jsdoc-ignore-code
# or using yarn cli
yarn add jsdoc-ignore-code
```


## Usage

Add plugin to jsdoc conf.json http://usejsdoc.org/about-configuring-jsdoc.html

```json
{
    "plugins": ["./node_modules/jsdoc-ignore-code/index"]
}
```

## Customize

add options to jsdoc conf.json

```json
{
    "plugins": ["./node_modules/jsdoc-ignore-code/index"],
    "ignoreCode": {
        "some-options": true,
        "another-options": false
    }
}
```

## Options

We just have only one parameter, for which this module was created

_In the future, we hope to develop it adding new opportunities.  
Or maybe one of you will want to add your solutions to ignore some parts of the code_

##### `dynamicImports`

type `boolean`  
default `true`  
Ignore dynamically importing ES modules `import()`



## Tests

Sorry but here no tests yet.

## To Do

write tests and more examples

## Contributing

You're welcome - [issues](https://github.com/dutchenkoOleg/jsdoc-ignore-code/issues) and [pulls](https://github.com/dutchenkoOleg/jsdoc-ignore-code/pulls)

