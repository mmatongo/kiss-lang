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


WIP LANGUAGES
---

- [-] C# - [status: build failing]
- [-] Java [status: on hold]
  - [-] Kotlin
  - [-] Scala
  - [-] Clojure
  - [-] Erlang
    - [-] Elixir
- [-] Julia [status: failing]
- [-] Zig [status: cannot build on musl (yet)]


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
    of weight to the package, it exists on the staging
    branch of my private repo for obvious reasons with the
    top one being that it is a very hacky solution that will
    be fixed in time.

PROPOSED
- I have thought about adding any and all depends on this
    repo separate from everything else, this is primarily so
    I can have some sort of established order. As it is the
    current meandry of repos leaves me with nothing but
    headaches.

UPDATES
- New repo structure will take effect soon, a few natable
  things however;
    - I decided to roll my own KISS based(for now) os @noirlinux 
        doing this has made it easier for me to incorporate
        changed to [gcc] that would normally not be accepted (I
        think).
    - I have also decided to not limit the scope of the repo
        and just add as many languages as I wanna and make
        it easier for anyone that wants to setup a dev
        station.
    - If you're using [noirlinux] then you might not need
        some elements from this repo as those are already
        hard baked into the preinstalled [gcc].
