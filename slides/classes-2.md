##  Classes

Static methods:

    class Circle {
      // ...

      static fromCircumference(circumference) {
        return new Circle(circumference / (2 * Math.PI));
      }
    }

Usage:

    var c = new Circle(5);
    console.log(c.calcArea());

    var c2 = Circle.fromCircumference(20);
    console.log(c2.radius);
