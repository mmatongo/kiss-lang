KISS LANGUAGE REPO
---

This is https://k1ss.org repo dedicated to language
compilers etc.

Because KISS is source based and pretty much every package
can be managed by anyone, I saw the need to make this repo
to put into one place the languages you might end up
needing.


AVAILABLE LANGUAGES
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
- [x] Janet
- [x] V [v-lang]
- [x] Chez Scheme
- [x] GForth
- [x] PForth
- [x] LuaJIT
- [x] Retro
- [x] C# (mono)
- [x] Java [non native]
- [x] Zig

WIP LANGUAGES
---

- [] Java-native [status: in progress]
- [-] Kotlin [status: in progress]
- [-] Scala [status: in progress]
- [-] Clojure [status: in progress]
- [-] Erlang [status: in progress]
  - [-] Elixir
- [-] Julia [status: failing]
- [-] F# (f-sharp)

REQUIREMENTS
---
In order to use this repo you need to have it set-up and pointing to your [KISS_PATH].

YOU ARE REQUIRED TO INSTALL [gcc-multilib] without it half
of this repo will not compile.

1.
---
If you want to contribute, provide some insight or anything of the kind, feel free to make a pull or open an issue.

NB
- A few of the languages i.e R and D required a slight
    modification to the [gcc] package, this modification is
    non-fatal but begs to be mentioned because it adds a lot
    of weight to the package, it exists on the extras branch
    branch of this repo. It is a very hacky solution that will
    be fixed in time (I really have no time).
