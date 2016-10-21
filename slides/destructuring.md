## Destructuring

Allows to easily access elements in an object or array

    var obj = {
      propA: 123,
      propB: 456,
      propC: 789,
    };
    var arr = [1, 2, 3];

    var { propA, propB } = obj;  // propC unused
    var [first, second, third] = arr;

    console.log(propA, propB);
    console.log(first, second, third);

Neat for importing only certain symbols from a module.
