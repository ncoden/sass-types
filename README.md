# Sass Types
✨ Awesome Type Checking in Sass

### Install with NPM
```
npm install ncoden/sass-types
```

:warning: This Sass module is still in development.

### Usage

```scss
@import 'sass-types';

@function my-function($number, $string) {
    $_: st-assert('my-function', (number $number, string $string));

    ...
}
```

Version 0.1.0 - MIT License.
