# ClangFormat Style Configuration File

This repository contains style configuration files for LLVM's ClangFormat automatic source code formatter. I created these style configuration files for use in my software projects. These files are licensed under the MIT license, so you may use them in your software projects subject to the terms of the license. For more information about the MIT license, see the [LICENSE](LICENSE) file or visit <https://mit-license.org>. For more information about LLVM's ClangFormat, visit <https://clang.llvm.org/docs/ClangFormat.html>.

The style configuration files are available for different versions of ClangFormat:

- [Version 17.0.0](17.0.0/.clang-format)
- [Version 16.0.0](16.0.0/.clang-format)
- [Version 15.0.0](15.0.0/.clang-format)
- [Version 14.0.0](14.0.0/.clang-format)
- [Version 13.0.0](13.0.0/.clang-format)
- [Version 12.0.0](12.0.0/.clang-format)
- [Version 11.0.0](11.0.0/.clang-format)

On Ubuntu, install ClangFormat with:

```BASH
sudo apt install clang-format
```

Check the version of ClangFormat with:

```BASH
clang-format --version
```

Format your source code files with:

```BASH
clang-format --style=file:path/to/style/configuration/file path/to/source/code/files
```

Alternatively, if you place a ClangFormat style configuration file named `.clang-format` or `_clang-format` in the root directory of your source code repository, you can format your source code files with:

```BASH
clang-format --style=file path/to/source/code/files
```

Additionally, most modern integrated development environments support source code formatting with ClangFormat directly within their user interface; consult your environment's documentation for more details.
