## 1.0.0 (2022-06-06)

### New features

First stable version.

## 0.16.0 (2022-04-20)

### Breaking changes

Move to 0.16 serialized parser format.

### New features

Add `CatchClause` and `FinallyClause` nodes wrapping parts of `TryStatement`.

The parser now includes syntax highlighting information in its node types.

## 0.15.3 (2022-01-26)

### Bug fixes

Support missing values in array pattern syntax.

Support quoted module export names.

## 0.15.2 (2021-12-08)

### Bug fixes

Fix a typo in the `TaggedTemplateExpression` node name. Support n suffixes after non-decimal integers

Add support for non-decimal bignum literals ().

Add support for static class initialization blocks.

## 0.15.1 (2021-11-12)

### Bug fixes

Add support for TypeScript `import {type X} from y` syntax.

Indexed TypeScript types can now take type parameters.

Add support for private field syntax.

Rename PropertyNameDefinition node to PropertyDefinition for consistency with other names.

### New features

Recognize TypeScript 4.3's `override` keyword.

## 0.15.0 (2021-08-11)

### Breaking changes

The module's name changed from `lezer-javascript` to `@lezer/javascript`.

Upgrade to the 0.15.0 lezer interfaces.

## 0.13.4 (2021-04-30)

### Bug fixes

Fixes a bug where arrow functions with expression bodies would include commas after the expression.

## 0.13.3 (2021-02-15)

### Bug fixes

Wrap escaped JSX attribute values in a `JSXEscape` node.

## 0.13.2 (2021-01-18)

### Bug fixes

Fix parsing of async function expressions.

## 0.13.1 (2020-12-04)

### Bug fixes

Fix versions of lezer packages depended on.

## 0.13.0 (2020-12-04)

## 0.12.0 (2020-10-23)

### Breaking changes

Adjust to changed serialized parser format.

## 0.11.1 (2020-09-26)

### Bug fixes

Fix lezer depencency versions

## 0.11.0 (2020-09-26)

### Breaking changes

Follow change in serialized parser format.

## 0.10.1 (2020-09-02)

### Bug fixes

Fix associativity of `else` and ternary operators.

Work around accidental ambiguity of TypeScript method and constructor signatures.

Properly parse `??=` as an update operator.

## 0.10.0 (2020-08-07)

### Breaking changes

Upgrade to 0.10 parser serialization

### New features

The gammar now supports TypeScript (use the `"ts"` dialect).

The grammar can now parse JSX syntax (use the `"jsx"` dialect).

## 0.9.1 (2020-06-29)

### Bug fixes

Fix accidental use of non-ES5 library methods.

## 0.9.0 (2020-06-08)

### Breaking changes

Upgrade to 0.9 parser serialization

## 0.8.4 (2020-05-30)

### Bug fixes

Fix the package.json `main` field pointing at the wrong file, breaking the library in node versions older than 13.

## 0.8.3 (2020-04-09)

### Bug fixes

Regenerate parser with a fix in lezer-generator so that the top node prop is properly assigned.

## 0.8.2 (2020-04-01)

### Bug fixes

Make the package load as an ES module on node

## 0.8.1 (2020-02-28)

### New features

Provide an ES module file.

## 0.8.0 (2020-02-03)

### Bug fixes

Add support for the spread ... operator in array literals.

### New features

Follow 0.8.0 release of the library.

Add support for nullish coalescing and optional chaining.

## 0.7.0 (2020-01-20)

### Breaking changes

Use the lezer 0.7.0 parser format.

## 0.5.2 (2020-01-15)

### Bug fixes

Regenerate with lezer-generator 0.5.2 to avoid cyclic forced reductions.

## 0.5.1 (2019-10-22)

### Bug fixes

Fix top prop missing from build output.

## 0.5.0 (2019-10-22)

### Breaking changes

Move from `lang` to `top` prop on document node.

## 0.4.0 (2019-09-10)

### Breaking changes

Adjust to 0.4.0 parse table format.

## 0.3.0 (2019-08-22)

### New features

Go back to node names, add props, follow changes in grammar syntax.

## 0.2.0 (2019-08-02)

### New features

Use tags rather than names.

## 0.1.0 (2019-07-09)

### New Features

First documented release.
