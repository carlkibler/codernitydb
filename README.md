CodernityDB
===========

A pure python, NoSQL, fast database. Clone from https://bitbucket.org/codernity/codernitydb/

CodernityDB is opensource, pure Python (no 3rd party dependency), fast (really fast check Speed if you don't believe in words), multiplatform, schema-less, NoSQL_ database. It has optional support for HTTP server version (CodernityDB-HTTP-link_), and also Python client library (CodernityDB-PyClient-link_) that aims to be 100% compatible with embeded version.

.. image:: http://labs.codernity.com/codernitydb/_images/CodernityDB.png
    :align: center


You can call it a more advanced key-value database. With multiple key-values indexes in the same engine. Also CodernityDB supports functions that are executed inside database.

Main documentation is located at http://labs.codernity.com/codernitydb


Key features
~~~~~~~~~~~~

* Native Python database
* Multiple indexes
* Fast (more than 50 000 insert operations per second see Speed for details)
* Embeded mode (default) and Server (CodernityDB-HTTP-link_), with client library that aims to be 100% compatible with embeded one
* Easy way to implement custom Storage


Install
~~~~~~~

Because CodernityDB is pure Python you need to perform standard installation for Python applications::

   pip install CodernityDB

or using easy_install::

   easy_install CodernityDB

or from sources::

   hg clone ssh://hg@bitbucket.org/codernity/codernitydb
   cd codernitydb
   python setup.py install



Contribute & Bugs & Requests
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

CodernityDB is one of projects developed and released by Codernity_, so you can contact us directly in any case.

Do you want to contribute? Great! Then just fork our repository `CodernityDB @ Bitbucket`_ and do a pull request. It can't be more easy!

To fill a bug please also use Bitbucket.


Support
~~~~~~~

In case of any problems, feature request you can also contact us directly.

Do you want customized version of CodernityDB ? No problem, just contact us.


.. _NoSQL: http://en.wikipedia.org/wiki/NoSQL
.. _KnockoutJS: http://knockoutjs.com/
.. _CodernityDB @ Bitbucket: http://bitbucket.org/codernity/codernitydb
.. _Codernity: http://codernity.com
.. _CodernityDB-HTTP-link: http://labs.codernity.com/codernitydb-http
.. _CodernityDB-PyClient-link: http://labs.codernity.com/codernitydb-pyclient
