## dom-event

## :warning: DEPRECATED :warning:

This module exists to fix some [kik/Azer](http://blog.npmjs.org/post/141577284765/kik-left-pad-and-npm) issues. New projects should not depend on this.

---

Add/remove DOM events

## Usage

```js
var on = require('dom-event')
var off = on.off

on(document.body, 'click', hello) // adds the event listener
off(document.body, 'click', hello) // removes

function hello () {
  console.log('hello!')
}
```
