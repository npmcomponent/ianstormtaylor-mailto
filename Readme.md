*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/mailto](http://github.com/ianstormtaylor/mailto). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-mailto`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# mailto

  Programmatically open the user's email client.

## Installation

    $ component install ianstormtaylor/mailto

## Example

```js
var mailto = require('mailto');

mailto('ian@ianstormtaylor.com', {
  subject: 'The mailto component...',
  body: 'It works!'
});
```

## API

### mailto(email, options)
  
  Draft a new message to an `email` address with `options`:

    {
      subject: String,
      body: String
    }

## License

  MIT
