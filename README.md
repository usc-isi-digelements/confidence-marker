# confidence-marker

A Polymer Element showing an marker that displays confidence and extraction information

### Example
```js
demo.extraction = {
	confidence: 100,
	provenance: [
		0: {
			method: 'method',
			source: {
				context: 'prevWord prevWord <etk> keyword </etk> postWord postWord',
				document_id: 'document id',
				segment:  'segment'
			}
		}
	]
}
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