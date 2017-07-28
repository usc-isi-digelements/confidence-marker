# confidence-marker

A Polymer Element showing an marker that displays confidence and extraction information

### Example
```js
demo.extraction = {
  confidence: 100,
  provenance: [{
    method: 'demoMethod',
    source: {
      context: {
        text: '2before 1before <etk> highlighted text</etk> 1after 2after'
      },
      segment: 'demoSegmet'
    }
  }]
};
```
```html
<confidence-marker
  extraction=[[extraction]]>
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