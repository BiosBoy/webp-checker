# WebP Checker

 [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=See&url=https://github.com/BiosBoy/webp-checker&via=svyat770&hashtags=js,jsx,webp,checker,webp-checker,webp,html,css)

### The easist way to check webp support in any browser!

[![npm](https://badgen.net/npm/v/webp-checker)](https://www.npmjs.com/package/webp-checker) [![Price](https://img.shields.io/badge/price-FREE-purple.svg)](https://github.com/BiosBoy/webp-checker/blob/master/LICENSE) [![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](https://github.com/BiosBoy/webp-checker/blob/master/LICENSE) [![GitHub package version](https://img.shields.io/badge/version-1.1.1-green.svg)](https://github.com/BiosBoy/webp-checker)

  

![logo_image](https://raw.githubusercontent.com/BiosBoy/webp-checker/master/web-checker_logo.jpg)

**How to use:**
  - Quick Start:
   So, to get know is your browser has webP support or not, basically, you need just to run `webpChecker`. 
   After function running you will get a `window` variable `__WEBPSUPPORT__` (e.g. `window.__WEBPSUPPORT__`) with boolean value that shows is webp support `true/false`.
  ```
    import webpChecker from 'webp-checker' // import it;

    webpChecker(); // run checker
    
    window.__WEBSUPPORT__ // get notified about browser webp support by this global variable
  ```

  - Advanced:
  In case when you need to set up a better custom config you can throw props as:
```
  const config = {
    imgURL: {your_webp_image_src, by default used google static image}
    disableGlobal: {disable global injection in 'window' object, by default 'false'},
    injectBodyClass: {explicitly set a 'body' class 'webp-support', by default 'true'},
    callback: {some callback that you want to return with webp checker result 'true/false'}
  }
```
