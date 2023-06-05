# ClangFormat Style Configuration File

This repository contains the ClangFormat style configuration file in use in my projects.

Visit <https://clang.llvm.org/docs/ClangFormatStyleOptions.html> for a list of ClangFormat style options with descriptions and examples.

Run ClangFormat with:

```BASH
clang-format --style=file:path/to/style/configuration/file path/to/source/code/file.cpp
```

ClangFormat version 15.0.0 supports these additional style options:

```YAML
IndentRequiresClause: false
InsertBraces: true
QualifierOrder: ['friend', 'static', 'volatile', 'inline', 'constexpr', 'const', 'restrict', 'type']
RequiresClausePosition: SingleLine
SpaceBeforeParensOptions:
  AfterRequiresInClause: true
  AfterRequiresInExpression: true
```

ClangFormat version 16.0.0 supports these additional style options:

```YAML
BreakAfterAttributes: Never
BreakArrays: false
BreakBeforeInlineASMColon: OnlyMultiline
InsertNewlineAtEOF: true
IntegerLiteralSeparator:
  Binary: 0
  BinaryMinDigits: 0
  Decimal: 0
  DecimalMinDigits: 0
  Hex: 0
  HexMinDigits: 0
LineEnding: DeriveLF
RemoveSemicolon: false
RequiresExpressionIndentation: OuterScope
```

ClangFormat version 17.0.0 supports these additional style options:

```YAML
BracedInitializerIndentWidth: 2
Macros: []
SpaceBeforeJsonColon: false
VerilogBreakBetweenInstancePorts: false
```
