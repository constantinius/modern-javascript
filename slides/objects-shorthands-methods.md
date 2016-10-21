##  Objects: Shorthands &amp; Methods

Makes object definition shorter and more readable:

    var attributeShorthand = "...";

    var obj = {
      attributeShorthand,

      someMethod() {
        console.log(this.attributeShorthand);
      },
    };
