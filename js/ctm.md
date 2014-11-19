# Cutting the mustard
The following cutting the mustard test is used as the baseline:

    if ('querySelector' in document && 'addEventListener' in window  && ("classList" in document.createElement("_")) && Object.prototype.toString.call(window.operamini) !== "[object OperaMini]") {
      document.querySelector('html').classList.add('js');
      // Initialise JS
    }
