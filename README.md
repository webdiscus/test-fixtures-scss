[![npm](https://img.shields.io/npm/v/@test-fixtures/scss?logo=npm&color=brightgreen "npm package")](https://www.npmjs.com/package/@test-fixtures/scss "download npm package")
[![node](https://img.shields.io/npm/dm/@test-fixtures/scss)](https://www.npmjs.com/package/@test-fixtures/scss)


# @test-fixtures/scss
This is a SCSS test fixture library to simulate a usage of SCSS from node modules.

## Install

```
npm i -D @test-fixtures/scss
```

## Usage

```scss
@use '@test-fixtures/scss' as fixture;

.primary {
  color: fixture.$primary;
}

.secondary {
  color: fixture.$secondary;
}

.success {
  color: fixture.$success;
}

.info {
  color: fixture.$info;
}

.warning {
  color: fixture.$warning;
}

.danger {
  color: fixture.$danger;
}
```
