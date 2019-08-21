# WebP Checker

How to use:
  - Quick Start:
   So, to get know is your browser has webP support or not, basically, you need just to run `webpChecker`. 
   After function running you will get a `window` variable `__WEBPSUPPORT__` (e.g. `window.__WEBPSUPPORT__`) with boolean value that shows is webp support `true/false`.
  ```
    import webpChecker from 'webp-checker' // import it;

    webpChecker(); // run checker
  ```

  - Advanced:
  In case when you need to set up a better custom config you can throw props as:
```
  const config = {
    imgURL: {your_webp_image_src}
    disableGlobal: {disable global injection in 'window' object},
    injectBodyClass: {explicitly set a 'body' class 'webp-support'},
    callback: {some callback that you want to return with webp checker result 'true/false'}
  }
```
