# Spek

Spek is an acoustic spectrum analyser written in C++. It uses FFmpeg
libraries for audio decoding and wxWidgets for the GUI.

Spek is available on BSD, GNU/Linux, Windows and Mac OS X.

![spek](https://github.com/artenax/spek/assets/107228652/841bcd34-09e0-4d4e-9592-78f9ff908aea)

## Spek 0.8.5 - Released 2023-01-09

### New Features And Enhancements

New features since 0.8.2:

 * Upgrade to FFmpeg 5.1
 * Add 2 more palettes and change the default.
 * Allow changing the DFT window size and function.
 * Allow switching between audio streams and channels.
 * Add translations for 14 additional languages.

Enhancements:

 * Remove dependency on `intltool`.
 * Fix FFmpeg build warnings.
 * Detect AR tool.
 * Use Homebrew for macOS dependencies.
 * Improve test coverage.
 * Use `XDG_CONFIG_HOME` on Unix systems.

Bugfixes:

 * Remove association with .mod and MIDI files.
 * Fix autoconf errors.
 * Fix an AVX-related crash.

### Dependencies

 * wxWidgets >= 3
 * A recent version of FFmpeg
