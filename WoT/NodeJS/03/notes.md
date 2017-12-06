## 3.5.1

# Async programming with Anonymous callbacks

Sequential models do not scale well. Node comes with two main patterns for dealing with async calls: i.e **callbacks and event listeners**

Consider a function F(X){} that performs an aysnc operation such as fetching data from a network. What will we need to express what happens next?
**Callback example** -
Whenever F(x){} returns we will assign another function to call. i.e. when F(x){} finishes, another function that will do the message sending.

### A function is passed as a parameter to an asynchronous function describing what to do after the async function has completed.

e.g. The anonymous function passed as an argument **database.query()** is a callback.

**Anonymous functions do not have names and unlike named callbacks they can't be called by any other code expect for the function they're passed to**

## always implement two parameters in callbacks, the first one being error and the other is what you're expecting back

```js

var request = require('request');
request('http://nannerl.io', function(error, response, body) {
  if (!error && response.statusCode === 200 ){
    console.log(body);
  }
});

```
**here the call to request takes a callback as a parameter. This is expected because the call will be executed asynchronously. With the request library.
