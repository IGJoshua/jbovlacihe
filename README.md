# la jbovlaci'e
La jbovlaci'e is a server project to provide the
[lojban](https://mw.lojban.org/) community with a modern alternative to the
[jbovlaste](https://jbovlaste.lojban.org/) dictionary. It provides a REST-ful
interface to words and definitions, with freedom for users to define words for
specific dialects, give feedback on definitions, and search.

## Rationale
Jbovlaste is a dated project and it provides no programmatic interface useful
for applications which want to interface with the dictionary. It provides no
method for having definitions of things evolve over time, or to have dialects
with individual definitions of words.

La jbovlaci'e is designed to solve as many of these problems as possible, and to
provide a definition of a good dictionary application to move into the future.
It is primarily a reference implementation of an api, and is designed to be easy
to re-implement, allowing applications which rely on it to work on different
instances, and for a new version to be developed if future developers dislike
the tool choices.

## Features
At launch, la jbovlaci'e is intended to have the following features:

- non-morphologically-restricted words
- multiple immutable definitions per word
- tags per definition to allow filtering
- Decaying votes per definition
- JVS-style export of full dictionary
- JSON export of full dictionary
- Securely stored and validated user accounts

## Known Issues

## Future Plans
As time goes on, additional features will be added. The following features are
planned.

- GraphQL compliant API
- Comment chains on definitions
- Hierarchical dialects with definition search
- User profile pictures (maybe)
- User bios

## License

Copyright © 2020 Joshua Suskalo

Distributed under the MIT License (Expat).
