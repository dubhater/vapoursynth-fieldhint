Description
===========

Fieldhint filter for VapourSynth.

This a port of the avisynth plugin.

Usage
=====

::

   fh.Fieldhint(clip clip, string ovr)

Compilation
===========

To compile the filter in 64 bit Linux (and possibly other Unix-like systems)::

   clang -O3 -Wall -Wextra -Wno-unused-parameter -fPIC -shared -o libfieldhint.so fieldhint.c
