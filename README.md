# A 32 Bit Interbase Driver for Python - [Based On FDB](http://www.firebirdsql.org/en/devel-python-driver/)

[Based On FDB](http://www.firebirdsql.org/en/devel-python-driver/) \*
[FDB Documentation](http://fdb.readthedocs.io/en/v2.0/) \* 
[FDB Source](https://github.com/FirebirdSQL/fdb) \* 
[Say Thanks to FDB](https://saythanks.io/to/pcisar)

Changes implemented are based on this blog post

[InterBase and Python (Gabe Goldfield - October 2 2015)](https://community.idera.com/developer-tools/b/blog/posts/interbase-and-python)

InterBase Driver for Python is a [Python](http://python.org) library package that implements
[Python Database API 2.0](http://www.python.org/dev/peps/pep-0249/)-compliant support for
the Embarcadero SQL Database
[InterBase](http://www.firebirdsql.org) ®. In addition to the minimal
feature set of the standard Python DB API, Interbase Driver for Python also exposes the entire
native (old-style) client API of the database engine. Notably:

  - Automatic data conversion from strings on input.
  - Automatic input/output conversions of textual data between UNICODE
    and database character sets.
  - Support for prepared SQL statements.
  - Multiple independent transactions per single connection.
    access specifications.
  - Distributed transactions.

Install (32-bit version of python required)

`pip install git+https://github.com/mknapper1/Python-Interbase`
