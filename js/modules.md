#JavaScript modules

    window.DECADE_CITY = (function(module) {

      module.SUBMODULE = (function(module, submodule) {

        return submodule;
      }(module, module.SUBMODULE || {});

      return module;
    }(window.DECADE_CITY || {}));

