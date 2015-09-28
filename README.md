# ng-notification-browserify

Simple implementation of ng-notification to browserify.

[ng-notification](https://www.npmjs.com/package/ng-notification)

## Install
```
npm i ng-notification-browserify
```


## Example

```javascript
var ngNotification = require('ng-notification-browserify');
// require return a string, use that string to load module on angular
angular.module('myApp', [ngNotification]);
```
Implementation works like [ng-notification](https://www.npmjs.com/package/ng-notification)
```html
<notification></notification>
```
