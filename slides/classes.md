##  Classes

Class Definition and Constructor:

    class Circle {
      constructor(radius) {
        this._radius = radius;
      }
    }

Methods and Properties:

    class Circle {
      // ...

      get area() {
        return this._area;
      }

      calcArea() {
        return this._radius * this._radius * Math.PI;
      }
    }
