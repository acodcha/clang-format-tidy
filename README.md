# ClangFormat Style Configuration File

This repository contains a style configuration file for LLVM's ClangFormat automatic source code formatter. I created this style configuration file for use in my software projects. The file is available for different versions of ClangFormat:

- [17.0.0](17.0.0/.clang-format)
- [16.0.0](16.0.0/.clang-format)
- [15.0.0](15.0.0/.clang-format)
- [14.0.0](14.0.0/.clang-format)
- [13.0.0](13.0.0/.clang-format)
- [12.0.0](12.0.0/.clang-format)
- [11.0.0](11.0.0/.clang-format)

For more information about LLVM's ClangFormat, visit:

- <https://clang.llvm.org/docs/ClangFormat.html>

For descriptions and examples of ClangFormat style options, visit:

- <https://clang.llvm.org/docs/ClangFormatStyleOptions.html>

On Ubuntu, install ClangFormat with:

```BASH
sudo apt install clang-format
```

Check the version of ClangFormat with:

```BASH
clang-format --version
```

Run ClangFormat with:

```BASH
clang-format --style=file:path/to/style/configuration/file path/to/source/code/file
```

Alternatively, if you place a ClangFormat style configuration file named `.clang-format` or `_clang-format` in the root directory of your repository, you can run ClangFormat with:

```BASH
clang-format --style=file path/to/source/code/file
```
