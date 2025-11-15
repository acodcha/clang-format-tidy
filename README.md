# Clang-Format and Clang-Tidy Configuration Files

Configuration files for LLVM's Clang-Format automatic source code formatter and LLVM's Clang-Tidy automatic source code linter.

I created these configuration files for use in my personal software projects. These files are licensed under the MIT license, so you may use them in your software projects subject to the terms of the license. For more information about the MIT license, see the [LICENSE](LICENSE) file or visit <https://mit-license.org>. For more information about LLVM's Clang-Format automatic source code formatter, visit <https://clang.llvm.org/docs/Clang-Format.html>. For more information about LLVM's Clang-Tidy automatic source code linter, visit <https://clang.llvm.org/extra/clang-tidy>

Contents:

- [Clang-Format Configuration File](#clang-format-configuration-file)
- [Clang-Tidy Configuration File](#clang-tidy-configuration-file)

## Clang-Format Configuration File

The configuration files are available for different versions of Clang-Format:

- [Clang-Format Configuration File for Version 18.0.0](clang-format/18.0.0/.clang-format)
- [Clang-Format Configuration File for Version 17.0.0](clang-format/17.0.0/.clang-format)
- [Clang-Format Configuration File for Version 16.0.0](clang-format/16.0.0/.clang-format)
- [Clang-Format Configuration File for Version 15.0.0](clang-format/15.0.0/.clang-format)
- [Clang-Format Configuration File for Version 14.0.0](clang-format/14.0.0/.clang-format)
- [Clang-Format Configuration File for Version 13.0.0](clang-format/13.0.0/.clang-format)
- [Clang-Format Configuration File for Version 12.0.0](clang-format/12.0.0/.clang-format)
- [Clang-Format Configuration File for Version 11.0.0](clang-format/11.0.0/.clang-format)

On Ubuntu, install Clang-Format with:

```BASH
sudo apt install clang-format
```

Check the version of Clang-Format with:

```BASH
clang-format --version
```

Format your source code files with:

```BASH
clang-format --style=file:/path/to/configuration/file /path/to/source/code/files
```

Alternatively, if you place a Clang-Format configuration file named `.clang-format` in the root directory of your source code repository, you can format your source code files with:

```BASH
clang-format --style=file /path/to/source/code/files
```

Additionally, most modern integrated development environments support source code formatting with Clang-Format directly within their user interface; consult your environment's documentation for more details.

[(Back to Top)](#clang-format-and-clang-tidy-configuration-files)

## Clang-Tidy Configuration File

The configuration file can be used with any version of Clang-Tidy:

- [Clang-Tidy Configuration File](clang-tidy/.clang-tidy)

On Ubuntu, install Clang-Tidy with:

```BASH
sudo apt install clang-tidy
```

Lint your source code files with:

```BASH
clang-tidy --config-file=/path/to/configuration/file --extra-arg=-std=c++20 /path/to/source/code/files
```

Alternatively, if you place a Clang-Tidy configuration file named `.clang-tidy` in the root directory of your source code repository, you can lint your source code files with:

```BASH
clang-tidy --extra-arg=-std=c++20 /path/to/source/code/files
```

Additionally, most modern integrated development environments support source code linting with Clang-Tidy directly within their user interface; consult your environment's documentation for more details.

[(Back to Top)](#clang-format-and-clang-tidy-configuration-files)
