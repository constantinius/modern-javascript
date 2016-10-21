##  Classes: Inheritance

Static methods:

    class SpecialCircle extends Circle {
      constructor(radius, specialValue) {
        super(radius);
        this.specialValue = specialValue;
      }

      calcArea() {
        return super.calcArea() + this.specialValue;
      }
    }

Usage:

    var c = new SpecialCircle(5, 2);
    console.log(c.calcArea());
