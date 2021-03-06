Installing :mod:`repoze.session`
================================

How To Install
--------------

You will need `Python <http://python.org>`_ version 2.4 or better to
run :mod:`repoze.session`.  Development of :mod:`repoze.session` is
done primarily under Python 2.4, so that version is recommended.
:mod:`repoze.session` does *not* run under any version of Python
before 2.4, and does *not* run under Python 3.X.

.. warning:: To succesfully install :mod:`repoze.session`, you will an
   environment capable of compiling Python C code.  See the
   documentation about installing, e.g. ``gcc`` and ``python-devel``
   for your system.  You will also need :term:`setuptools` installed
   on within your Python system in order to run the ``easy_install``
   command.

It is advisable to install :mod:`repoze.session` into a
:term:`virtualenv` in order to obtain isolation from any "system"
packages you've got installed in your Python version (and likewise, to
prevent :mod:`repoze.session` from globally installing versions of
packages that are not compatible with your system Python).

After you've got the requisite dependencies installed, you may install
:mod:`repoze.session` into your Python environment using the following
command::

  $ easy_install -i http://dist.repoze.org/lemonade/dev/simple repoze.session

What Gets Installed
-------------------

When you ``easy_install`` :mod:`repoze.session`, various Zope
libraries and ZODB are installed.
