# ghidra_fidb

## usage
### set all library files
```
<compiler>/<library>/<version>/<variant>/*.o
```

### import all library files
```bash
$ <ghidra_install_dir>/support/analyzeHeadless <proj_dir> <proj_name> \
    -import <compiler> \
    -recursive \
    -analysisTimeoutPerFile 600 \
    -scriptPath <ghidra_install_dir>/Ghidra/Features/FunctionID/ghidra_scripts \
    -preScript FunctionIDHeadlessPrescript.java \
    -postScript FunctionIDHeadlessPostscript.java
```

### make fidb file
```bash
$ <ghidra_install_dir>/support/analyzeHeadless <proj_dir> <proj_name> \
    -noanalysis \
    -scriptPath ./ghidra_scripts \
    -preScript CreateMultipleLibrariesHeadless.java \
    <duplicate_results_file> <output_fidb_file> <compiler> <language_id>
```

## reference
- https://github.com/NationalSecurityAgency/ghidra/blob/master/Ghidra/Features/FunctionID/ghidra_scripts/CreateMultipleLibraries.java
- https://github.com/threatrack/ghidra-fid-generator
