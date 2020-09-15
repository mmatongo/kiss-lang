## KISS LANGUAGE REPO
---

This is [KISS Linux](https://k1ss.org) repo dedicated to language
compilers etc.

Because KISS is source based and pretty much every package
can be managed by anyone, I saw the need to make this repo
to put into one place the languages you might end up
needing.



#### WHY ANOTHER REPO
---

Why not?

#### AVAILABLE LANGUAGES
---

- [x] Nim
- [x] Haskell
- [x] Go
- [x] Lua
- [x] Ocaml
- [x] R
- [x] Ruby
- [x] Vala
- [x] Racket (Minimal)

#### WIP LANGUAGES
---

- [x] Crystal
- [x] C#
- [x] Java
  - [x] Kotlin
  - [x] Scala
  - [x] Clojure
  - [x] Erlang
    - [x] Elixir
- [x] D
- [x] Zig


#### REQUIREMENTS
---

Work is already in motion to make it so that you can build
the packages of this repo without the need for any other
repo but the community repo.
But until then the following is necessary.

In order to use this repo you need to have the following
repos set-up and pointing to your ``KISS_PATH``.

1.
```
$ git clone https://github.com/mmatongo/kiss.git
$ cd kiss
$ for i in -- $(ls -d -- */); do export KISS_PATH=$PWD/$i:$KISS_PATH:; done
```


You will need some packages in the above repo located in the
`staging`, `testing`, and `android` directories.

2. 
You will also need [@eudaldgr](https://github.com/eudaldgr)'s repo
```
$ git clone https://github.com/eudaldgr/kiss-repo
$ cd kiss-repo
$ for i in -- $(ls -d -- */); do export KISS_PATH=$PWD/$i:$KISS_PATH:; done
```


---
If you want to contribute, provide some insight or anything of the kind, feel free to make a pull or open an issue.
