# cljsjs/peg

[](dependency)
```clojure
[cljsjs/peg "0.8.0-0"] ;; latest release
```
[](/dependency)

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the ClojureScript compiler. After adding the above dependency to your project
you can require the packaged library like so:

```clojure
(ns application.core
  (:require cljsjs.peg))
```

Usage documentation [for PEG.js](http://pegjs.org/).

[flibs]: https://github.com/clojure/clojurescript/wiki/Packaging-Foreign-Dependencies
