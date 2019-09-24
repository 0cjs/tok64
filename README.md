Multi-platform TOK64
====================

> __NOTE:__ Currently this code does not compile.

This is modification of the original [tok64 source code][tok64] to
"genericise" it enough to compile on Linux, and hopefully other
platforms. (The original had things like backslashes in paths given to
`#include`.) A `Makefile` is now provided, and it's tested on Debian 9.

The original (ASCII) [README](README) file has been left untouched.

The changes are designed to be minimal, so I have left the source
filenames in upper case (though I generate a lower-case output file),
left them with DOS CR-NL end-of-line convention, etc. The commit
history of this repository gives the details of what changes were
made.



<!-------------------------------------------------------------------->
[tok64]: https://github.com/thezerobit/tok64
