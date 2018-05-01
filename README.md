# extract

Have you ever extracted an archive, only to find you with plenty of file cluttering your folder? 
Well, extract takes care of that.

This is a script extracts an archive, but look first inside it, counting how many files do we have at the top level.
If there is more than one file (a single folder), then it proceeds by creating a folder of the base name of the archive and extracts its content into the newly created folder. Another one of its feature is to extract several archives in parallel, the number of processes used being set by the user.


extract supports the following archive/compression formats:
- .tar.bz2
- .tar.gz
- .bz2
- .tar
- .tbz2
- .tgz
- .gz
- .zip
- .rar
- .7z

