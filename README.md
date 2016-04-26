# angular-currency-filter
This angular module filters your numbers and creates well formatted currency string.

## Usage

Download file, insert your page and add dependencies.
```javascript
var app = angular.module( 'myapp', ['currencyModule'] );
```

HTML markup: add country code, or use browser settings.
```html
<span>{{ price | currencyFilter:'US' }}</span>
```

Thats it!


