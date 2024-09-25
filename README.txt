built from modified busybox-w32 source, hacky af

compilers used: GNU binutils (homebrew), gcc (homebrew, and custom),
                LLVM/Clang (homebrew), /usr/bin/ld (apple stock linker),
                lld (homebrew)

built on my crappy x86_64 macbook air running macOS 12,
arm64 build is crossed (build cross gcc from source first

TODO:
  - fix timespec thing so stat and touch SUSv3 extension can work
  - fix network stuff so wget can work
