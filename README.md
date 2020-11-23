## KISS LANGUAGE REPO
---

This is [KISS Linux](https://k1ss.org) repo dedicated to language
compilers etc.

Because KISS is source based and pretty much every package
can be managed by anyone, I saw the need to make this repo
to put into one place the languages you might end up
needing.


#### AVAILABLE LANGUAGES
---

- [x] Nim
- [x] Haskell
- [x] Go
- [x] Lua
- [x] Ocaml
- [x] R [r-lang]
- [x] Ruby
- [x] Vala
- [x] Racket (Minimal)
- [x] Crystal
- [x] Fortran (Technically a compiler)
- [x] D [d-lang]


#### WIP LANGUAGES
---

- [x] C# - [status: build failing]
- [x] Java [status: on hold]
  - [x] Kotlin
  - [x] Scala
  - [x] Clojure
  - [x] Erlang
    - [x] Elixir
- [x] Julia [status: failing]
- [x] Zig [status: cannot build on musl (yet)]


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

#### NB
- A few of the languages i.e R and D required a slight
    modification to the `gcc` package, this modification is
    non-fatal but begs to be mentioned because it adds a lot
    of weight to the package, it exists on the staging
    branch of my private repo for obvious reasons with the
    top one being that it is a very hacky solution that will
    be fixed in time.

#### PROPOSED
- I have thought about adding any and all depends on this
    repo separate from everything else, this is primarily so
    I can have some sort of established order. As it is the
    current meandry of repos leaves me with nothing but
    headaches.
