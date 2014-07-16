# go.lang

ALL CREDIT GOES TO [PETER EISENTRAUT](http://savannah.gnu.org/users/petere).
---

syntax highlighting for golang using gnu source-highlight.

let's you get go syntax highlighting from `less`!

taken from [here](http://savannah.gnu.org/patch/?8031).

you'll need to

    $ ln -s path/to/go.lang/go.lang path/to/source-highlight/version/share/source-highlight/go.lang
    $ echo "go = go.lang" >> path/to/source-highlight/version/share/source-highlight/lang.map

(make sure that `go = go.lang` is on its own line)
