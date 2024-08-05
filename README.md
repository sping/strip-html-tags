# Strip HTML Tags

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Strip HTML tags from string.

## Installation

`yarn add @sping/strip-html-tags`
`npm install @sping/strip-html-tags`

## Usage

1. Import stripHtmlTags in your .js file
`@import stripHtmlTags`
2. running `stripHtmlTags('<div class="hello">strip me</div>')` will return `'strip me'`

## Commands

- `npm run clean` - Remove `lib/` directory
- `npm test` - Run tests with linting and coverage results.
- `npm test:only` - Run tests without linting or coverage.
- `npm test:watch` - You can even re-run tests on file changes!
- `npm test:prod` - Run tests with minified code.
- `npm run test:examples` - Test written examples on pure JS for better understanding module usage.
- `npm run lint` - Run ESlint with airbnb-config
- `npm run cover` - Get coverage report for your code.
- `npm run build` - Babel will transpile ES6 => ES5 and minify the code.
- `npm run prepublish` - Hook for npm. Do all the checks before publishing your module.
