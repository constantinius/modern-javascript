##  Asynchronous Code: Async/Await

On top of Promises but traditional code structures.

Adds two concepts ``async`` functions and ``await``ing of values.

Return value of ``async`` function always a Promise

Await replaces the ``.then`` and ``.catch`` calls.

    try {
      var response = await fetch('http://example.com');
      var text = await response.text();
      console.log(text);
    } catch(error) {
      console.error('Something went wrong: ' + error);
    }
