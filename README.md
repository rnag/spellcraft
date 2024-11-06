# spellcraft

[![PyPI version](https://img.shields.io/pypi/v/spellcraft.svg)](https://pypi.org/project/spellcraft/)
[![Python versions](https://img.shields.io/pypi/pyversions/spellcraft.svg)](https://pypi.org/project/spellcraft/)
[![Documentation Status](https://readthedocs.org/projects/spellcraft/badge/?version=latest)](https://spellcraft.readthedocs.io/en/latest/)
[![Build Status](https://github.com/rnag/spellcraft/workflows/build-and-release/badge.svg)](https://github.com/rnag/spellcraft/actions)
<!-- [![Coverage Status](https://coveralls.io/repos/github/rnag/spellcraft/badge.svg?branch=main)](https://coveralls.io/github/rnag/spellcraft?branch=main) -->
[![License](https://img.shields.io/pypi/l/spellcraft.svg)](https://github.com/rnag/spellcraft/blob/main/LICENSE)
<!-- [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black) -->

`spellcraft` is a helper library that contains useful functions and "spells," primarily designed for use with [Dataclass Wizard].

This library exists to provide case conversion between common cases like
CamelCase and snake_case. It is intended to be unicode aware, internally
consistent, and reasonably well performing.

[Dataclass Wizard]: https://dataclass-wizard.readthedocs.io/

## Cases contained in this library:

1. UpperCamelCase
2. lowerCamelCase
3. snake_case
4. kebab-case
5. SHOUTY_SNAKE_CASE
6. Title Case
7. SHOUTY-KEBAB-CASE
8. Train-Case

## License

`spellcraft` is distributed under the terms of the MIT License.

See the LICENSE file for full details.

> Copyright (c) 2015 The Rust Project Developers<br>
> Copyright (c) 2022 Kevin Heavey<br>
> Copyright (c) 2024 Ritvik Nag
