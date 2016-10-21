##  Miscellaneous: Generators

Just like Python generators :)

    function* myGenerator() {
      yield 1;
      yield 2;
      yield 3;
    }

    for (var v of myGenerator()) {
      // ...
    }

IE does not support Generators :(
