# Windows batch file - Concatenate all files in subdirectories

https://stackoverflow.com/questions/11711569/windows-batch-file-concatenate-all-files-in-subdirectories

From the command line you can use (e.g.):
```
>concat.js (for /r "c:\javascripts" %F in (*.js) do @type "%F")
```

*I used the following to create a new file called #concat.md#
```concat.md (for /r "C:\Users\im494c\Desktop\Misc\1" %F in (*.md) do @type "%F")```