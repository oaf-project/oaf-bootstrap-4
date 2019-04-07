[![npm](https://img.shields.io/npm/v/oaf-bootstrap-4.svg)](https://www.npmjs.com/package/oaf-bootstrap-4)

# Oaf Bootstrap 4

Accessibility fixes for Bootstrap 4.

## Installation

```sh
# yarn
yarn add --dev oaf-bootstrap-4

#npm
npm install --save-dev oaf-bootstrap-4
```

## Usage

You'll need to recompile Bootstrap's Sass yourself.

Assuming `src/styles/index.scss`:

```scss
// Accessibility fixes that need to come _before_ the Bootstrap import.
@import "../../node_modules/oaf-bootstrap-4/scss/top.scss";

// Bootstrap itself.
@import "../../node_modules/bootstrap/scss/bootstrap.scss";

// Accessibility fixes that need to come _after_ the Bootstrap import.
@import "../../node_modules/oaf-bootstrap-4/scss/bottom.scss";

// Other styles.
...
```

## Bootstrap 3

For a similar library for Bootstrap 3, see [bootstrap-hacks](https://github.com/danielnixon/bootstrap-hacks).
