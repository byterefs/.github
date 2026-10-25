# byterefs

**Byte references**: a specification for describing data as references to
byte ranges in existing files and objects, so that large archives can be read
as virtual datasets without copying or reformatting them.

A byte reference says "the bytes for this piece of data live at this location,
from this offset, for this length, encoded like this". Collections of such
references can present many files in many formats as a single, consistent,
cloud-friendly dataset.

## Status

Early days. The specification is being drafted in
[byterefs/spec](https://github.com/byterefs/spec); expect things to change.

## Get involved

- Read the [contributing guide](https://github.com/byterefs/.github/blob/main/CONTRIBUTING.md).
- Open an issue to ask a question or propose a change.
- Please follow our [code of conduct](https://github.com/byterefs/.github/blob/main/CODE_OF_CONDUCT.md).
