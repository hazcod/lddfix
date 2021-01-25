# lddfix
Script to fix any linked libraries for your executable to make it static.

If your binary is not compiled statically it requires specific libraries to be in place.
This script copies all required libraries to `./static/` and patches your binary paths using `patchelf`.
