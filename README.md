# confidence-marker

A Polymer Element showing the confidence of an extraction that opens a dialog with the provenance details of that extraction.

### Example
```js
var provenances = [{
  method: 'html extraction',
  text: 'the quick brown fox <etk>jumped</etk> over the lazy dog'
}];
```

```html
<confidence-marker
  confidence="100"
  document-id="1234"
  provenances="[[provenances]]">
</confidence-marker>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve
