# ClangFormat Style Configuration File

This repository contains the ClangFormat style configuration file in use in my projects.

Different ClangFormat style configuration files are available for different versions of ClangFormat:

- [ClangFormat version 12.0.0](12.0.0/.clang-format)
- [ClangFormat version 13.0.0](13.0.0/.clang-format)
- [ClangFormat version 14.0.0](14.0.0/.clang-format)
- [ClangFormat version 15.0.0](15.0.0/.clang-format)
- [ClangFormat version 16.0.0](16.0.0/.clang-format)
- [ClangFormat version 17.0.0](17.0.0/.clang-format)

For a list of ClangFormat style options with descriptions and examples, visit:

- <https://clang.llvm.org/docs/ClangFormatStyleOptions.html>

Run ClangFormat with:

```BASH
clang-format --style=file:path/to/style/configuration/file path/to/source/code/file.cpp
```

Alternatively, if you place a ClangFormat style configuration file named `.clang-format` or `_clang-format` in the root directory of your repository, you can run ClangFormat with:

```BASH
clang-format --style=file path/to/source/code/file.cpp
```
