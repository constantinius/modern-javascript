##  Asynchronous Code: Promises - Create

How to create a Promise:

    var promise = new Promise(
      function(resolve, reject) {
        // ...
        if (condition) {
          resolve(value);
        } else {
          reject(new Error("Something went wrong"));
        }
      }
    );
