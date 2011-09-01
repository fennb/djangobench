Djangobench
===========

A hacked up version of Djangobench that compares performance of django running under cpython vs pypy.

Running the benchmarks
----------------------

Setup a virtualenv (or other environment) that has both cpython and pypy available.

Here's the short version::

    pip install -e git://github.com/fennb/djangobench.git#egg=djangobench
    svn co http://code.djangoproject.com/svn/django/tags/releases/1.3/ django-control
    djangobench

