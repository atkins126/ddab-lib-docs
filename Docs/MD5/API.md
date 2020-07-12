# [MD5 Message Digest Unit](../MD5.md) Programmers Guide

## Introduction

This section of the MD5 Message Digest Unit documentation focusses on describing the classes and records contained in the unit.

There is just one unit in this project, named _PJMD5_ that contains all the code.

## Contents

This guide is divided into the following sections:

* [TPJMD5](./API/TPJMD5.md) -- class used to generate message digests.
* [TPJMD5Digest](./API/TPJMD5Digest.md) -- record that encapsulates a message digest.
* [EPJMD5](./API/EPJMD5.md) -- class of exceptions generated by code in the unit.


## Conventions

Identifiers in plain text appear like this: _Identifier_

Identifiers in links appear like this: [_Identifier_](#conventions)

Values and in-line code appear like this:

* `42`
* `'text'`
* `True`
* `X := 42;`

When an item or statement applies only to a later version of the project it will be marked with the earliest version number of the project to which it applies. For example: [v1.1]

Declarations and source code examples appear syntax highlighted like this:

```pascal
procedure Foo(const Bar: string);
```

## Links

* [Project Overview](./Overview.md) -- details of the purpose of the unit.
* [How-to Guide](./HowTo.md) -- various examples of how to use the unit.