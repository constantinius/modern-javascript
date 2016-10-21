##  Modules: Import

Allows to import symbols from other modules:

    import 'someModule';  // all globals are now available

    import someModule from 'someModule';

    someModule.someFunction()

This works great with the Object Destructuring:

    import { someFunction, someVariable } from 'someModule';

    someFunction(someVariable);
