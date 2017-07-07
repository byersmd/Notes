# Windows batch file - Concatenate all files in subdirectories

https://stackoverflow.com/questions/11711569/windows-batch-file-concatenate-all-files-in-subdirectories

From the command line you can use (e.g.):
```
>concat.js (for /r "c:\javascripts" %F in (*.js) do @type "%F")
```

where:
```
FOR %variable IN (set) DO command [command-parameters]

  %variable  Specifies a single letter replaceable parameter.
  (set)      Specifies a set of one or more files.  Wildcards may be used.
  command    Specifies the command to carry out for each file.
  command-parameters
             Specifies parameters or switches for the specified command.
             
FOR /R [[drive:]path] %variable IN (set) DO command [command-parameters]

    Walks the directory tree rooted at [drive:]path, executing the FOR
    statement in each directory of the tree.  If no directory
    specification is specified after /R then the current directory is
    assumed.  If set is just a single period (.) character then it
    will just enumerate the directory tree.
    
# @type /?
Displays the contents of a text file or files.

TYPE [drive:][path]filename    
```


*I used the following to create a new file called #concat.md#
```
concat.md (for /r "C:\Users\im494c\Desktop\Misc\1" %F in (*.md) do @type "%F")
```

