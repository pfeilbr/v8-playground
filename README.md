# V8 Playground

Project to learn and experiment with the [V8](https://developers.google.com/v8/) javascript engine.

## Building V8 with Xcode

1. Install [depot-tools](http://dev.chromium.org/developers/how-tos/install-depot-tools).  And add to `PATH` environment variable.
2. Clone repo
    $ git clone https://chromium.googlesource.com/v8/v8.git
3. Build
    $ cd v8
    $ build/gyp_v8 -Dtarget_arch=x64

## Background

This project was created with a new `Application | Command Line Tool` with the language set to `C++` in Xcode.

The static libraries from the v8 build were copied in
![](http://note.io/1c3cOzl)

The v8 include files were copied from `v8/include` to `v8-includes`

## Resources

* [Google V8 Docs](https://developers.google.com/v8/)