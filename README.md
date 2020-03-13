# Static Qt 5.6.3 build for Windows XP without SSE2

This repository contains Qt 5.6.3 sources with a script meant to build a static
version of the library with MSVC static runtime, as well as additional fixes
meant to make the build runnable on Windows XP with a processor without any
additional instruction set extensions.

Keep in mind that this does not aim to be a complete build of the library, as
only the `qtbase`, `qtmultimedia`, `qttools`, `qttranslations` and
`qtwebsockets` modules are being built.

A [static build of OpenSSL](https://github.com/xavery/openssl10-static-xp) is
included in the library. OpenSSL code will be included in the resulting
executables built with this Qt build if you use the `network` module in your
application.
