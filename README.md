# delphi-uses-formatter

Formats uses sections of pascal files

Formatting follows this style:

```
uses
  AllUnitsAreAlphabeticallySorted,
  UnitA,
  UnitB,
  UnitC;
```

The extension gets activated on pascal and objectpascal languages or on first command use.

command: pascal-uses-formatter.formatUses

settings:

pascal-uses-formatter.formatOnSave: when the extension is activated it also auto formats on save.


[![Build Status](https://dev.azure.com/tuncbahcecioglu/delphi-uses-formatter-CI/_apis/build/status/tuncb.delphi-uses-formatter?branchName=master)](https://dev.azure.com/tuncbahcecioglu/delphi-uses-formatter-CI/_build/latest?definitionId=1&branchName=master)
