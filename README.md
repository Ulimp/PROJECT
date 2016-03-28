Семестровый проект на PYTHON
My project is an ordinary banner (Linux) with horizontal exit. Windows console is bad, but so far I'm not ready to move on Linux, because I will write in cygwin. Tag Parsing a complicated procedure for me, so I will replace them on the output setting using command line parameters. Below is an approximate functional.

Usage: bannerp [OPTION].. [TEXT]
Options:

-c    char=[CHAR] Print TEXT with symbols CHAR
-C    char-color=[COLOR] Print colored text. White by default
-r     random-chars Print TEXT with random ASCII letters
-x    Print TEXT with its own symbols

-s     space=[SPACE] Print TEXT using SPACE as space and background symbols
-S    space-color=[COLOR] Print colored spaces and background. Black by default
-w    space-width=[N] Space width

-z     zoom=[N] Zoom text font N times
-W    word-wrap Wrap words if terminal size is too small
-m    char-set=[MODULE] Using specified char set

-l     list-colors List supported colors
-L    list-char-sets List available char sets
-h    help Print this message and exit
-v    version Print program version and exit

If TEXT is not specified, reads standart input.
