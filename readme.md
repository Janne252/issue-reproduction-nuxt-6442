# Instructions (Windows 10 only!)

## Entry points
These batch scripts automatically install all dependencies, start the local development server, and launch the development server URL in a browser.


## 1. `install-at-once.bat` (bug reproduction)
To reproduce the issue, run `install-at-once.bat`.


#### Expected result
```
Failed to show Nuxt.js app after 5 reloads
```

----

## 2. `install-in-series.bat` ("fix")
To demonstrate a "fix" (really a workaround) for the issue, run `install-in-series.bat`.


#### Expected result
```html
<h1>Is nuxt development server getting stuck?</h1>
```