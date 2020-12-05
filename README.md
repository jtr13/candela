# This is a clone

Please see the official repo for this package: https://github.com/Kitware/candela/tree/master/R/candela

This clone was created since I had trouble installing candela from a subdirectory with GitHub Actions: 

```
Error: Error: <callr_remote_error: No root directory found in /tmp/Rtmp8zbHEH/file52aa6a60c11c/src/contrib/candela_0.2.0_51d7b2b94aa75a3ec94a804310ca85249143d61b.tar.gz-tree-tree
or its parent directories. Root criterion: contains a file "DESCRIPTION">
```
https://github.com/jtr13/cc20/runs/1496541945?check_suite_focus=true

It worked once I moved `Kitware/candela/R/candela` to its own repo: `jtr/candela`.
