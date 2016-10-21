##  Asynchronous Code: Promises - Usage

How to consume a promise:

    var promise = ...;

    promise
      .then(function(value) {
        // do something with the value
        // ...
        return newValue;
      })
      .then(function(newValue) {
        // use newValue
      })
      .catch(function(error) {
        // handle the error
      });
