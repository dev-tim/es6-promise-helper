Simple ES6 promise helper for creating Promise object
in defined state with better syntax.

I reused the same thing in different projects so I decided 
to make it a separate module.

##Installation
Just execute:

```
 npm install --save es6-promise-helper
```

##Examples 

ES6 promise helper usually used in tests or anywhere where you 
need to have shorthand to get resolved or rejected promises.

For example:

```

var promiseHelper = require('es6-promise-helper');

// returns resolved promise with a value
promiseHelper.when(yourValue);
 
// returns rejected promise with an error
promiseHelper.fail(new Error('connection error');


```



## Questions and contribution

Feel free to make any suggestions, open issue or make PR. 