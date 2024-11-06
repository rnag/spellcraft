.. PySpellCraft documentation master file, created by
   sphinx-quickstart on Tue Nov  5 22:23:32 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

PySpellCraft
============

.. Add your content using ``reStructuredText`` syntax. See the
.. `reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_
.. documentation for details.

**spellcraft** is a utility or "helper" library primarily designed
for use in the `dataclass-wizard <https://dataclass-wizard.readthedocs.io>`_ library, facilitating
various case conversions.

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
