# {%= name %} {%= badge("fury") %}

> {%= description %}

{%= include("install-npm", {save: true}) %}

## Usage

```js
var <%= _.namify(appname) %> = require('{%= name %}');
```

## API
{%= apidocs("index.js") %}


## Run tests

Install dev dependencies:

```bash
node i -d && mocha
```

## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue]({%= bugs.url %})

## Author
{%= include("author") %}

## License
{%= copyright() %}
{%= license() %}

***

{%= include("footer") %}