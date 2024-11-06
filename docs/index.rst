.. PySpellCraft documentation master file, created by
   sphinx-quickstart on Tue Nov  5 22:23:32 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

PySpellCraft
============

.. Add your content using ``reStructuredText`` syntax. See the
.. `reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_
.. documentation for details.

.. _PyPI version badge:
   https://pypi.org/project/spellcraft/

.. image:: https://img.shields.io/pypi/v/spellcraft.svg
   :target: https://pypi.org/project/spellcraft/

.. _Python versions badge:
   https://pypi.org/project/spellcraft/

.. image:: https://img.shields.io/pypi/pyversions/spellcraft.svg
   :target: https://pypi.org/project/spellcraft/

.. _Docs Status badge:
   https://ritviknag.com/spellcraft/

.. image:: https://github.com/rnag/spellcraft/actions/workflows/docs.yml/badge.svg
   :target: https://ritviknag.com/spellcraft/

.. _Build Status badge:
   https://github.com/rnag/spellcraft/actions/workflows/build-and-release.yml/badge.svg
   :target: https://github.com/rnag/spellcraft/actions/workflows/build-and-release.yml

.. _License badge:
   https://img.shields.io/pypi/l/spellcraft.svg
   :target: https://github.com/rnag/spellcraft/blob/main/LICENSE

.. image:: https://img.shields.io/pypi/l/spellcraft.svg
   :target: https://github.com/rnag/spellcraft/blob/main/LICENSE

**spellcraft** is a helper library that contains useful functions and "spells", primarily designed
for use by `Dataclass Wizard <https://dataclass-wizard.readthedocs.io>`_.

This library aims to be Unicode-aware, internally consistent,
and reasonably performant, providing convenient case conversion
between common naming conventions.

Supported Cases
---------------

1. UpperCamelCase
2. lowerCamelCase
3. snake_case
4. kebab-case
5. SHOUTY_SNAKE_CASE
6. Title Case
7. SHOUTY-KEBAB-CASE
8. Train-Case

.. PySpellCraft is merely a wrapper around a Rust library `heck <https://docs.rs/heck/latest/heck/>`_.
.. Most of this documentation is copied lovingly from the ``heck`` docs.

.. note::
    Each ``spellcraft`` function has a ``_many`` counterpart that operates on a sequence of strings.
    For example, the ``snake`` function converts a single string to snake case, while
    ``snake_many`` converts a sequence of strings into a list of snake case strings.
    The ``_many`` functions achieve high performance by taking advantage of Rust's parallel features,
    so you should use them in places where they make sense.

Installation
------------

::

    pip install spellcraft

Note: requires Python >= 3.9.

API
---

.. automodule:: spellcraft
    :imported-members:
    :members:
    :undoc-members:

.. toctree::
   :maxdepth: 2
   :caption: Contents:

.. toctree::
    :caption: Changes and License
    :maxdepth: 1

    change-log
    license
