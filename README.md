StrongHelp User Interface Toolbox Manual
========================================

This project contains the source files for the StrongHelp User Interface Toolbox reference manual [hosted on riscos.info](http://www.riscos.info/downloads/stronghelp/manuals/).


Conventions
-----------

The source files are stored within the `src/` folder, in sub-folders which match the names of the completed StrongHelp manuals.

Filenames contain the same characters as used in the finished manual, except that `/` in a RISC OS filename is mapped to `.`. Filetypes should always be explicitly included on the ends of filenames using the conventional `,xxx` extension format -- for example `!Root,fff` or `!Root,ffd`. The names of directories appear in exactly the same format as the finished manual, and have no trailing filetype specifier.

The contents of files should be exactly as they will appear on RISC OS: no Unicode characters, RISC OS (or Linux) line endings, and so on. No translation is carried out on the files' contents, so *take care when editing files on non-RISC OS platforms* to ensure that encodings remain as Latin-1.


Building on Linux
-----------------

The files are intended to be assembled in a Linux environment using the BindHelp tool, from within the main [StrongHelp Manuals project](https://github.com/riscos-dot-info/stronghelp-manuals).


Contact
-------

Initial work on this project was carried out by Steve Fryatt -- info@stevefryatt.org.uk