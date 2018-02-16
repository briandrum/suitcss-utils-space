# SUIT CSS utilities: space

Spacing utilities for SUIT CSS

## Installation

* Download: [zip](https://github.com/briandrum/suitcss-utils-space/releases/latest)

## Available classes

**`inset`**

* `u-spaceInsetQuarterEx` - 
* `u-spaceInsetHalfEx` - 
* `u-spaceInsetThreeQuarterEx` - 
* `u-spaceInsetOneEx` - 
* `u-spaceInsetOneAndAHalfEx` - 
* `u-spaceInsetTwoEx` - 
* `u-spaceInsetThreeEx` - 
* `u-spaceInsetFourEx` - 
* `u-spaceInsetEightEx` - 

**`inset squish`**

* `u-spaceInsetSquishExtraSmall` - 
* `u-spaceInsetSquishSmall` - 
* `u-spaceInsetSquishMedium` - 
* `u-spaceInsetSquishLarge` - 
* `u-spaceInsetSquishExtraLarge` - 

**`inset stretch`**

* `u-spaceInsetStretchExtraSmall` - 
* `u-spaceInsetStretchSmall` - 
* `u-spaceInsetStretchMedium` - 
* `u-spaceInsetStretchLarge` - 
* `u-spaceInsetStretchExtraLarge` - 

**`inline left`**

* `u-spaceInlineLeftHalfEx` - 
* `u-spaceInlineLeftThreeQuarterEx` - 
* `u-spaceInlineLeftOneEx` - 
* `u-spaceInlineLeftOneAndAHalfEx` - 
* `u-spaceInlineLeftTwoEx` - 

**`inline right`**

* `u-spaceInlineRightHalfEx` - 
* `u-spaceInlineRightThreeQuarterEx` - 
* `u-spaceInlineRightOneEx` - 
* `u-spaceInlineRightOneAndAHalfEx` - 
* `u-spaceInlineRightTwoEx` - 

**`stack`**

* `u-spaceStackQuarterEx` - 
* `u-spaceStackHalfEx` - 
* `u-spaceStackThreeQuarterEx` - 
* `u-spaceStackOneEx` - 
* `u-spaceStackOneAndAHalfEx` - 
* `u-spaceStackTwoEx` - 
* `u-spaceStackThreeEx` - 
* `u-spaceStackFourEx` - 
* `u-spaceStackEightEx` - 

### Plugins

All space utilities can be limited to specific Media Query breakpoints.

* `u-sm-spaceInsetX` - To use at the smallest Media Query breakpoint.
* `u-md-spaceInsetX` - To use at the medium Media Query breakpoint.
* `u-lg-spaceInsetX` - To use at the largest Media Query breakpoint.

``` html
<div class="u-spaceInsetHalfEx u-md-spaceInsetOneEx u-lg-spaceInsetTwoEx">
  <!-- content -->
</div>
```

### Configuration

There are 3 Media Query breakpoints:

* `--sm-viewport`
* `--md-viewport`
* `--lg-viewport`

When using [postcss-custom-media](https://github.com/postcss/postcss-custom-media),
breakpoints can be configured using `@custom-media`. For example:

```css
@custom-media --sm-viewport (min-width:320px) and (max-width:640px);
@custom-media --md-viewport (min-width:640px) and (max-width:960px);
@custom-media --lg-viewport (min-width:960px);
```

## Testing

Install [Node](http://nodejs.org) (comes with npm).

```
npm install
```

To generate a build:

```
npm run build
```

To lint code with [postcss-bem-linter](https://github.com/postcss/postcss-bem-linter) and [stylelint](http://stylelint.io/)

```
npm run lint
```

To generate the testing build.

```
npm run build-test
```

To watch the files for making changes to test:

```
npm run watch
```

Basic visual tests are in `test/index.html`.

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 28+
* Safari 6.1+
* Internet Explorer 10+
