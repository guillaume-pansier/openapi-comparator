# [WIP] Open API Comparator

A simple comparator able to detect differences between 2 versions of an API based on its Open API specifications.

## Installation

The tool will soon be available as a nuget package.

## Code Samble

```C#
var comparator = new OpenApiComparator();

var messages = comparator.Compare(
    oldSpecName,
    oldSpec,
    newSpecName,
    newSpec
);
```

## Documentation

Each comparison rule is domentated in the [documentation section](https://github.com/criteo/openapi-comparator/tree/main/documentation).

## License

OpenApi Comparator is an Open Source software released under the [Apache 2.0 license](https://github.com/criteo/openapi-comparator/blob/main/LICENCE).


