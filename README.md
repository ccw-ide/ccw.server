# ccw.server

Library that needs to be present in your application classpath so that CCW tooling works great when connected via nrepl.

## Usage

* Put `[ccw/ccw.server "0.1.0"]` into the `:dependencies` vector of your project.clj.
* Add a repl option to automatically require namespace `ccw.debug.serverrepl`

    :dependencies [[ccw/ccw.server "0.1.0"]]
    :repl-options {:init (require 'ccw.debug.serverrepl)}

## How does it work?


## Todo


## License

Copyright © 2013 Laurent Petit

Distributed under the Eclipse Public License, the same as Clojure.
