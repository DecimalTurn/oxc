# Exit code
0

# stdout
```
  ! eslint(no-debugger): `debugger` statement is not allowed
   ,-[files/index.js:1:1]
 1 | debugger;
   : ^^^^^^^^^
   `----
  help: Remove the debugger statement

  ! basic-custom-plugin(no-debugger): Unexpected Debugger Statement
   ,-[files/index.js:1:1]
 1 | debugger;
   : ^^^^^^^^^
   `----

Found 2 warnings and 0 errors.
Finished in Xms on 1 file using X threads.
```

# stderr
```
WARNING: JS plugins are experimental and not subject to semver.
Breaking changes are possible while JS plugins support is under development.
```
