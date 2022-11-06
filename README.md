# findgrep - Code for Assignment 1 for ILSE, 04-801 B2, Fall 2022

__Usage__: $SCRIPTNAME [options] <egrep-pattern>"
Search patterns recursively in a directory files


    #  \033[1mUSAGE\033[0m: $SCRIPTNAME - Search patterns recursively in a directory's files 
    #
    #  \033[1mSYNOPSIS
    #
    # \t $SCRIPTNAME [OPTIONS] <egrep-pattern>\033[0m
    #
    #  \033[1mDESCRIPTION\033[0m
    #
    #  Recursively searches files in and below a given directory (by default, the current directory) for a specified regular expression. 
    #  By default, the search will examine only C and C++ files—that is,  those that end in .c, .cpp, h, or .hpp
    #  But this can be overridden via command line options.
    #
    #  \t\033[1m <egrep-pattern>\033[0m is an extended regular expression as used by grep -E
    #
    # \t \033[1mOptions can be one or more of:\033[0m
    #
    # \t --c \t\t\t\t mode (the default): search files ending in .c, .h, .cpp and .hpp
    # \t --py \t\t\t Python mode: search files ending in .py, .json, and .xml
    # \t --text \t\t\t Text mode: search files ending in .txt, .texi, .md, or beginning with the name README.
    # \t --all \t\t\t Look at all files, not just C/C++ files
    # \t -h | --help \t\t Print this usage message and exit
    # \t -i | --insensitive \t Perform case insensitive search (default is case sensitive)
    # \t --top <rootdir> \t\t Set the root directory of the search; default is cwd
    # \t --up \t\t\t Set the root of the search to parent of cwd; equivalent to --top=..
    #
    #  \033[1mAUTHOR\033[0m
    #
    # \t Written by parmenin (Niyomwungeri Parmenide ISHIMWE) at CMU-Africa - MSIT 
    #
    #  \033[1mDATE\033[0m 
    #
    # \t November 6, 2022" 
