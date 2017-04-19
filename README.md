# Opinionated Python3 only pytest Koans

An interactive tutorial for learning Python3 with all the new bells and whistles by making tests pass.

Grown from [gregmalcolm/python_koans](https://github.com/gregmalcolm/python_koans).

## How?

Most tests are *fixed* by filling the missing parts of assert functions. E.g.:

    assert mu == 1 + 2

which can be fixed by replacing [mu](https://en.wikipedia.org/wiki/Mu_(negative)) with the appropriate expression:

    assert 3 == 1 + 2

Occasionally you will encounter some failing tests that are already filled out. In these cases you will need to finish implementing some code to progress. For example, there is an exercise for writing some code that will tell you if a triangle is equilateral, isosceles or scalene.

As well as being a great way to learn some Python, it is also a good way to get a taste of Test Driven Development (TDD).

## Install Python 3.6+

You need **Python 3.6 or newer** for this:

    https://www.python.org/downloads/

If you have problems making your first steps:

    http://www.python.org/about/gettingstarted

## Install the Koans

**FIXME** make this happen

    $ git clone https://github.com/obestwalter/python_koans
    $ cd python_koans
    $ pip install -e .
