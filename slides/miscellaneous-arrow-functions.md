##  Miscellaneous: Arrow Functions

Like functions but some improvements: shorter, binds ``this``, single expressions

Forms:

    () => { /* body */ }  // no arguments,
    arg1 => { /* body */ }  // single argument
    (arg1, arg2) => { /* body */ }  // multiple arguments argument

    (arg1, arg2) => (arg1 + arg2)  // single expression body

Examples:

    var values = [1, 2, 3, 4];
    var sum = values.reduce((a, b) => a + b);
    var evens = values.filter(v => (v % 2) === 0);
    var squares = values.map(v => v * v);
