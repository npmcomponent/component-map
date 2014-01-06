*This repository is a mirror of the [component](http://component.io) module [component/map](http://github.com/component/map). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-map`.*

# map

  Map utility

## Installation

    $ component install component/map

## API

### map(array, fn)

  Map returning a new array:

```js
var names = map(users, function(user){
  return user.name;
});
```

### map(array, string)

  Map properties in `string` returning a new array:

```js
var names = map(users, 'user.name');
var firstNames = map(users, 'user.name.first');
```

# License

  MIT
