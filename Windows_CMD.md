# Windows batch file - Concatenate all files in subdirectories

https://stackoverflow.com/questions/11711569/windows-batch-file-concatenate-all-files-in-subdirectories

From the command line you can use:
,,,
>concat.js (for /r "c:\javascripts" %F in (*.js) do @type "%F")
,,,