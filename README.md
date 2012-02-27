#### Linked In throwdown
A clojure + clojurescript consideration of Linked In's client-side javascript throwdown -
http://engineering.linkedin.com/frontend/client-side-templating-throwdown-mustache-handlebars-dustjs-and-more

This project uses clojurescript or clojure and the same set of templates to generate html on the client or server.

#### Usage

lein deps
lein cljsbuild clean
lein cljsbuild once
lein repl
(load "linked-in/dev_server")
(linked-in.dev-server/run-server)

browse http://localhost:8080

#### License
This project uses a file from Brenton Ashworth's One project
  https://github.com/brentonashworth/one
specifically
  https://github.com/brentonashworth/one/blob/master/src/lib/cljs/one/browser/remote.cljs
for client server communication