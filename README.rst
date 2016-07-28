Boost.Build Toolsets for IAR Systems Compilers
==============================================

.. contents::

Overview
--------

This directory contains Boost.Build toolsets for the IAR Systems
cross-compilers and documentation.

Toolset
-------

See the `documentation <iar.rst>`__ for a description of how to use
IAR Systems compilers.

See the implementation files for the toolset for implementation
details for toolset.

* `IAR C/C++ Compiler for ARM <iccarm.jam>`__

Testing
-------

This project can be tested using the `Boost.Build Toolset Tester
<https://github.com/tee3/boost-build-toolset-tester>`__.  There is a
branch ``devel-iar``, which configures the toolsets.

.. code:: sh

   $ b2 --test-config=user-config.jam \
         toolset=iccarm \
         link=static
