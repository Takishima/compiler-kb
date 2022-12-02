# Compiler knowledge base

A small knowledge base about compilers

# Preprocessor

## Get pre-defined macros

```bash
clang -x c /dev/null -dM -E
gcc -x c /dev/null -dM -E
```

```Powershell
echo '' | clang-cl /EP /d1PP /TP -
cl /EP /Zc:preprocessor /PD empty.cpp
```
