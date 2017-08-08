# instaparse-fail

```
lein trampoline cljsbuild repl-rhino
```

in `cljs.user`

``` clojure
(require '[instaparse.core :as insta])
(insta/parser
    "S = AB*
     AB = A B
     A = 'a'+
     B = 'b'+")
```

Boom
