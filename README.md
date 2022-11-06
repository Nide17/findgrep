# findgrep - Code for Assignment 1 for ILSE, 04-801 B2, Fall 2022
    
__USAGE__: findgrep - Search patterns recursively in a directory's files 

 __SYNOPSIS__
 
 __findgrep [OPTIONS] <egrep-pattern>__
    
 __DESCRIPTION__
    
 Recursively searches files in and below a given directory (by default, the current directory) for a specified regular expression. 
 By default, the search will examine only C and C++ files—that is,  those that end in .c, .cpp, h, or .hpp
 But this can be overridden via command line options.
    
 __<egrep-pattern>__ is an extended regular expression as used by grep -E
    
__Options can be one or more of:__
    
&nbsp; --c mode (the default):  search files ending in .c, .h, .cpp and .hpp
    
&nbsp; --py                      Python mode: search files ending in .py, .json, and .xml
    
&nbsp; --text                    Text mode: search files ending in .txt, .texi, .md, or beginning with the name README.
    
&nbsp; --all                     Look at all files, not just C/C++ files
    
&nbsp; -h | --help               Print this usage message and exit
    
&nbsp; -i | --insensitive        Perform case insensitive search (default is case sensitive)
    
&nbsp; --top <rootdir>           Set the root directory of the search; default is cwd
    
&nbsp; --up                      Set the root of the search to parent of cwd; equivalent to --top=..
    
 __AUTHOR__
    
 Written by parmenin (Niyomwungeri Parmenide ISHIMWE) at CMU-Africa - MSIT 
    
 __DATE__
    
 November 6, 2022" 
