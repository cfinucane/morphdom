Changelog
=========

# 1.x

## 1.4.x

### 1.4.1

- Use hard coded constants for node types for improved browser compatibility

### 1.4.0

- Make attributes and elements namespace-aware ([@shawnbot](https://github.com/shawnbot))

## 1.3.x

### 1.3.1

- Upgraded to `lasso@^2`
- Fixed tests

### 1.3.0

- Support full page html diff ([@DylanPiercey](https://github.com/DylanPiercey))

## 1.2.x

### 1.2.0

- Improve node lifecycle options ([@callum](https://github.com/callum))

## 1.1.x

### 1.1.4

- Checking in `dist/` files into the git repo
- Deleted `.cache/` from npm package

### 1.1.3

- Added a minified UMD distribution file

### 1.1.2

- Minor internal changes

### 1.1.1

- Updated `package.json`

### 1.1.0

- Fixes [#32](https://github.com/patrick-steele-idem/morphdom/issues/32) - Support for IE7+

## 1.0.x

### 1.0.4

- Fixes [#30](https://github.com/patrick-steele-idem/morphdom/issues/30) - Not all keyed elements are matched up correctly in some cases. Walk target DOM els that are moved over to match all keyed els.

### 1.0.3

- Added `getNodeKey` option - [Pull Request](https://github.com/patrick-steele-idem/morphdom/pull/28) by [Riim](https://github.com/Riim)

### 1.0.2

- Fixes [#21](https://github.com/patrick-steele-idem/morphdom/issues/21) - Caret position should not change if value did not change

### 1.0.1

- Fixes [#19](https://github.com/patrick-steele-idem/morphdom/issues/19) - Textarea problems