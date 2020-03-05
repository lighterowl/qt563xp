# Static Qt 5.6.3 build for Windows XP

This repository contains Qt 5.6.3 sources with a script meant to build a static
version of the library with MSVC static runtime, as well as additional fixes
meant to make the build runnable on Windows XP.

Keep in mind that this does not aim to be a complete build of the library, as
only the `qtbase`, `qtmultimedia`, `qttools` and `qttranslations` modules are
being built.
