# Opinionated Python3 only pytest Koans

[![Project Status: WIP - Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip)


## TODO

### Port all tests

... use pytest features

### Modernize with new idioms

f-strings and whatever ...

### Recreate test framework purely with pytest

* use [hooks](https://docs.pytest.org/en/latest/_modules/_pytest/hookspec.html) to customize
    * output
    * progress (x out of y tests; x out of y modules)
    * order?

bonus:

* random python quotes (not just zen)

----

## What?

An interactive tutorial for learning Python3 with all the new bells and whistles by making tests pass.

Grown from [gregmalcolm/python_koans](https://github.com/gregmalcolm/python_koans).

## How?

### Install Python 3.6+

You need [**Python 3.6 or newer**](https://www.python.org/downloads/) for this. If you just get started with Python, have a look at [this](http://www.python.org/about/gettingstarted).

### Install the Koans

**FIXME** make this happen

    $ git clone https://github.com/obestwalter/python_koans
    $ cd python_koans
    $ pip install -e .

### Start your path to enlightenment

Most tests are *fixed* by filling the missing parts of assert functions. E.g.:

    assert mu == 1 + 2

which can be fixed by replacing [mu](https://en.wikipedia.org/wiki/Mu_(negative)) with the appropriate expression:

    assert 3 == 1 + 2

Occasionally you will encounter some failing tests that are already filled out. In these cases you will need to finish implementing some code to progress. For example, there is an exercise for writing some code that will tell you if a triangle is equilateral, isosceles or scalene.

As well as being a great way to learn some Python, it is also a good way to get a taste of Test Driven Development (TDD).
