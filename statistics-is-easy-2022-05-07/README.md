## Setup instructions
1. Start a repl, and jack in. The project uses the deps.edn to import dependencies. Instructions are different for different editors
2. I will be running the workshop with neovim/conjure using clojure-vim/vim-jack-in to start a repl
3. Run the two lines of the commented code in the namespace.
```
(comment (clerk/serve! {:browse? true
               :watch-paths ["."]})
         (clerk/show!))
```
The notebook should appear in the browser at (http://localhost:7777)

See you at the workshop

