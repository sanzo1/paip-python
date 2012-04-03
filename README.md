paip-python
===========

Python implementations of some of the classic AI programs from Peter Norvig's
fantastic textbook "Paradigms of Artificial Intelligence Programming."


## Overview

This is meant to be a learning resource for beginning AI programmers.  It is no
longer common for students to have a background in Lisp programming, as many
universities have replaced Lisp with other languages in introductory programming
and introductory artificial intelligence courses.  It is my hope that making the
programs from PAIP available in a commonly-taught language will provide a useful
hands-on resource for beginning AI students.

I am writing these programs while reading through PAIP, so consider this a work
in progress.  Additionally, I am not at this time focusing on the end-of-chapter
exercises, which typically propose extensions to the programs to avoid various
limitations.  I hope that these Python programs are clean translations and don't
try to force Lisp idioms onto Python.

You can follow the progress of the project on [Trello][].


## Running

- You need [Python 2.7][]
- [Download][] the paip-python code.
- Type `python run_examples.py` and follow the prompts to run the examples.
- To use the Prolog interpreter, run `./prolog.py`.  Run it with the `-h` option
  for more details on its use and capabilities.


## Documentation

Literate programming-style documentation is available by running `python
build_docs.py` or on the web at http://dhconnelly.com/paip-python.  Each major
program is documented, containing an overview of its design and implementation
as well as links to example programs that use the algorithms it provides.


## About

These programs were written by [Daniel Connelly][homepage] as an independent
project supervised by [Professor Ashok Goel][goel].


[homepage]: http://www.dhconnelly.com
[goel]: http://home.cc.gatech.edu/dil/3
[Download]: https://github.com/dhconnelly/paip-python/zipball/master
[Trello]: https://trello.com/board/paip-python/4f4ba053201012e46306e5f0
[Python 2.7]: http://python.org/download/releases/2.7.2/
