# findgrep - Code for Assignment 1 for ILSE, 04-801 B2, Fall 2022

__Usage__: $SCRIPTNAME [options] <egrep-pattern>"
Search patterns recursively in a directory files


    #  _USAGE_: $SCRIPTNAME - Search patterns recursively in a directory's files 
    #
    #  _SYNOPSIS_
    #
    #  _$SCRIPTNAME [OPTIONS] <egrep-pattern>_
    #
    #  _DESCRIPTION_
    #
    #  Recursively searches files in and below a given directory (by default, the current directory) for a specified regular expression. 
    #  By default, the search will examine only C and C++ files—that is,  those that end in .c, .cpp, h, or .hpp
    #  But this can be overridden via command line options.
    #
    #  _ <egrep-pattern>_ is an extended regular expression as used by grep -E
    #
    # _Options can be one or more of:_
    #
    #  --c    mode (the default): search files ending in .c, .h, .cpp and .hpp
    # --py    Python mode: search files ending in .py, .json, and .xml
    # --text Text mode: search files ending in .txt, .texi, .md, or beginning with the name README.
    # --all  Look at all files, not just C/C++ files
    # -h | --help Print this usage message and exit
    # -i | --insensitive Perform case insensitive search (default is case sensitive)
    # --top <rootdir> Set the root directory of the search; default is cwd
    # --up  Set the root of the search to parent of cwd; equivalent to --top=..
    #
    #  _AUTHOR_
    #
    #  Written by parmenin (Niyomwungeri Parmenide ISHIMWE) at CMU-Africa - MSIT 
    #
    #  _DATE_
    #
    #   November 6, 2022" 
