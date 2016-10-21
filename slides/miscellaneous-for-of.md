##  Miscellaneous: 'for (... of ...)'

Allows the iteration over collections (Arrays, Maps, Sets, ...).

    var map = Map([['a', 1], ['b', 2]]);
    for (var [key, value] of map) {
      // ...
    }

Iterator protocol:

    var iterable = {
      [Symbol.iterator]() {
        return {
          i: 0,
          next() {
            if (this.i < 3) {
              return { value: this.i++, done: false };
            }
            return { value: undefined, done: true };
          }
        };
      }
    };
