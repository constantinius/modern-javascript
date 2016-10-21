##  Modules: Export

Defines what symbols of a source file are visible (importable):

    function myPrivateFunction() {}
    export function myExportedFunction() {}

"Default" exports: the module "is" the exported symbol.

    export default class {
      // ...
    }

Exported can be functions, classes and variables.
