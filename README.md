# jQuery Cool Grid

calclate item's height and show items

## Installation

Please include script after the jQuery library

```js
<script src="/path/to/jquery.coolgrid.js"></script>
```

## Usage

```js
options = {
  autoResize: true,
  container: $('.items'),
  offset: 5,
  item_width: 210
}

$('.item').CoolGrid(options);
```

## Development

This plugin is developed using coffeescript.

```
npm install -g coffee-script
coffee -c jquery.coolgrid.coffee
```


## License

### MIT
https://github.com/jquery/jquery-color/blob/2.1.2/MIT-LICENSE.txt