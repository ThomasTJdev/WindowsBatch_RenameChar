# Rename chars in filenames

This batch script rename filenames. The batch script needs to be placed in the same folder as the files, which it is checking.

## Config

Change the code accordingly to your needs. The example below has 4 renaming criterias. `+©` will be changed to `A`, etc.

```
REM Replace statements:
SET str=!str:+©=A!  
SET str=!str:+ÿ=d!  
SET str=!str:+ª=C!  
SET str=!str:W=!  
```

## Run

Navigate to folder in cmd.exe and run the file `changeCharFilename.bat`
