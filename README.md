### libass-android-builder

A simple shell script to cross-compile libass project for Android targets.

Builds the binaries and libs using static linking.

Typical usage:
```
bash ./build.sh
```

Requirements:
- Android SDK & NDK
- Autotools (autoconf, automake, libtool)
- prebuilt FreeType (via libfreetype-android-builder)
- prebuilt FriBidi (via libfribidi-android-builder)
- prebuilt HarfBuzz (via harfbuzz-android-builder)
- some dev tools
