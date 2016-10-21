##  Spreading and Rest

Spreading allows to unpack the contents of an array into another array or as
function parameters:

    var values = [1, 2, 3, 4];
    var otherValues = [0, ...values, 5, 6, 7];

    var myFunction = function(a, b, c, d) { }
    myFunction(...values);

Also works for array destructuring:

    var [first, second, ...rest] = [1, 2, 3, 4, 5, 6, 7];

Rest parameters allows to easily implement variable argument functions:

    var myFunction = function(a, b, ...rest) { };
    myFunction(1, 2, 3, 4, 5, 6);
    /*         a  b [   rest   ] */
