# ora-text-loaders
Create cool ora spinners with text inside.

![Examples](https://raw.githubusercontent.com/korobaka/ora-text-loaders/master/assets/examples.gif)

## Installation
You can install the package with [npm](https://npmjs.com) or [yarn](https://yarnpkg.com).

Command[:](https://www.youtube.com/watch?v=MoB8QTIvv8E) `npm i --s ora-text-loaders` OR `yarn install ora-text-loaders`

## Usage

Quick example:

```javascript
const ora = require('ora');
const texts = require('ora-text-loaders');
const loader = ora({spinner: texts.generate("Hello world!")});
loader.start("Testing!");
```

## Bugs / improvements
Found a bug, or want to improve something? thanks a lot! You can go on [this link](https://github.com/korobaka/ora-text-loaders/issues) to report a bug or suggest an improvement. Any pull request is welcome too!

