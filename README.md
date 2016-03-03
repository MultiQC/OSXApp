# MultiQC_OSXApp

### This plugin is depreciated!
This OSX app for MultiQC is no longer being developed. It should still work
with the very old version of MultiQC included with this repository, however
you're better off just grabbing the latest version of MultiQC and running
it on the command line..

---

**MultiQC is a tool to aggregate bioinformatics results across many
samples into a single report.**

This repository contains files to build the Mac OS X App version of MultiQC.
For information about the package, please see the
[main repository branch](https://github.com/ewels/MultiQC).

---

The OS X app is built using [Platypus](http://sveinbjorn.org/platypus).

To make the app work in as many places as possible, the distribution
includes a python virtual environment with all required dependencies (idea from
[here](http://apple.stackexchange.com/questions/159611/including-python-script-dependencies-virtualenv-contents-in-platypus)).

If anyone has any suggestions for how to better package this app, please
get in touch!
