robotpy-cppheaderparser
=======================

|Build Status|

CppHeaderParser is a pure python C++ header parser that parses C++
headers and creates a data structure that you can use to do many types
of things. We’ve found it particularly useful for creating programs that
generate python wrappers around existing C++ programs.

robotpy-cppheaderparser is a fork of the `CppHeaderParser`_ library
originally created by @senex. CppHeaderParser is an excellent library
and critical to some of the stuff we do in the RobotPy project.
Unfortunately, the maintainer seems to be busy, so
robotpy-cppheaderparser was born.

We don’t currently intend to develop new features, but aim to maintain
compatibility with the existing code and make improvements and bugfixes
as we need them.

If you find an bug, we encourage you to submit a pull request! New
changes will only be accepted if there are tests to cover the change you
made (and if they don’t break existing tests).

Documentation
-------------

Documentation can be found at https://cppheaderparser.readthedocs.io

Install
-------

::

   pip install robotpy-cppheaderparser

License
-------

BSD License

Authors
-------

Originally developed by Jashua Cloutier, this fork is maintained by the
RobotPy project.

Past contributors include:

* Jashua Cloutier
* Chris Love
* HartsAntler

.. _CppHeaderParser: https://bitbucket.org/senex/cppheaderparser

.. |Build Status| image:: https://travis-ci.org/robotpy/robotpy-cppheaderparser.svg?branch=master
   :target: https://travis-ci.org/robotpy/robotpy-cppheaderparser