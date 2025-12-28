## mj
hello! [my name's **Marijonas Minkus**, but most people call me **MJ**](https://512b.dev/mjm/portfolio).  
i'm an amateur software developer, in case my presence on this site didn't make it clear enough.

i am currently studying computer science, mathematics, and engineering in college ([college](https://en.wiktionary.org/wiki/college#English:_Q7533204), not the other one) at portsmouth. after this, i intend to take a computer science MEng, partially to further my skill, and partially because i like learning this stuff.

i've been programming since i was about nine years old. additionally, in my earlier years of learning, i was cursed with unlimited internet access, and so ended up with another (smaller, less hierarchically relevant) curse, that of being exposed to the Esoteric Programming community. essentially, Weird Code.

this has developed into a profound interest in just about every single field of programming that exists, but especially programming language design and low level systems development. (in my projects, those overlap far more often than you'd think. see [Forth](https://en.wikipedia.org/wiki/Forth_(programming_language)) (i am unreasonably obsessed with Forth ([see hvm although heph itself isn't well documented](https://codeberg.org/ufrag/hvm))))

alongside my more mentally strenuous interests, i also started, own, and run [a website with a few of my dev friends from around the world](https://512b.dev/) (if by the world we, of course, are talking about Europe and a bit of the Middle East). they're very cool people and are all in some small part responsible for my interests.

(p.s., you may look at my repo-less account and think it's a bit dodgy - all my projects are up on [my codeberg](https://codeberg.org/ufrag), not here! this account is for networking and contributions to projects hosted here)

### tools
in my day to day life, i use:
* **thinkpad X390**; light, fits in my bag, 16GiB of RAM and 256GiB of SSD; works wonderfully
* **alpine linux** on my laptop, with lxqt and openbox; it's small and pleasant
* **vim** for text editing; no real customisation past adjusting tabulation size
* **C99** for low-level programming; i generally use `zig cc` for compilation for its good caching
* **make** for build processes; it works
* **lua 5.1** for high-level programming; i use luajit because it's fast as hell
* **nasm** for x86 osdev stuff; it works
* ...along with some custom tooling for e.g. document rendering

### project bulletin
a seldom-updated list of the ideas i'm currently pursuing and (hopefully) developing

* heph: a toolchain built around a format which completely serialises a forth system in a full platform-agnostic manner, allowing one to write an operating system that runs at native speed on just about any processor with (at least) 16 bit addressing
* motex: a top-down sandbox / surrealist exploration game built with [lua](https://www.lua.org/), [LÖVE](https://love2d.org/), and my own [llecs](https://codeberg.org/ufrag/llecs)
* rv86: a very simple real mode bootloader for x86 systems, implementing reset vector semantics similar to that of the 6502 processor

### project back-burner
a likewise seldom-updated list of ideas i'm still interested in but am not presently working on

* bravo: a statically typed, compiled programming language with a focus on strong and elegant metaprogramming (inspired in part by Rust and Zig)
* bytehut: a minimal microblogging service built with lua and my own [llxml](https://codeberg.org/ufrag/llxml) (on hiatus because networking in lua sucks)
* sip: a simple protocol intended for state exchange and synchronisation between nodes within a single decentralised service
