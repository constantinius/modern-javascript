##  Asynchronous Code: Promises - Example

"Fetch" API - Intention to supersede XHR.

    fetch('http://example.com/')
      .then(function(response) {
        return response.text();  // returns another Promise
      })
      .then(function(text) {
        console.log(text);  // consume the final value
      })
      .catch(function(error) {
        console.error('Something went wrong: ' + error);
      });
