iced-coffee-script-middleware
=============================

Express Middleware for Iced Coffee Script

## Usage

```js
myCoffeeScript = require './libs/iced-coffee-script-middleware'

app.configure ->
	app.use myCoffeeScript.middleware {
		src: __dirname + '/public'
	}
	app.use express.static __dirname + '/public'
```
