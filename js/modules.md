#JavaScript modules
JavaScript code is organised into submodules of a main `window.DECADE_CITY` module using the following structure:

    window.DECADE_CITY = (function(module) {

      module.SUBMODULE = (function(module, submodule) {

        return submodule;
      }(module, module.SUBMODULE || {});

      return module;
    }(window.DECADE_CITY || {}));

As a general principle, no code is run on inclusion of the submodule, it should contain an `init` function that is explicitly called.

