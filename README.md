# vim-ci

This is an attempt to bring some build automation to Vim.

You can use this to check the build status of the latest Vim version or to test your own patches.
It currently only builds for Linux, but might eventually support OS X (through Travis) and Windows (through AppVeyor).

Feedback and contributions welcome!

## Build of the latest Vim version

[![Build Status](https://travis-ci.org/chrisbra/vim-ci.svg)](https://travis-ci.org/chrisbra/vim-ci)

<<<<<<< HEAD
You can see the build results at https://travis-ci.org/chrisbra/vim-ci. Builds are currently triggered manually,
=======
You can see the build results at https://travis-ci.org/chrisbra/builds. Builds are currently triggered manually,
>>>>>>> aafc00ff2a2f3fa504bc2a2f7b33da1753987767
but might eventually run at fixed intervals (e.g. once every day).

## How to test Vim patches

 1. Fork and clone this repository.
 2. Add the patches you want to test to the `patches/` directory.
 3. Commit these changes and create a pull request to this repository.

This will trigger a Travis build, which will apply the patch, compile Vim and run the tests.
