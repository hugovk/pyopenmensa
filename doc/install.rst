Install PyOpenMensa
===================

Currently only installation via git__ is supported, but building packages is planned (help is welcome).

__ http://git-scm.com/


Requirements
------------

* **Python >= 3.4**, Python 2.7 is currently also supported, but Python 3 is recommended.

No additional packages or libraries are needed.


Via git
-------

.. code-block:: bash

    git clone git://github.com/mswart/pyopenmensa


Via git submodule
-----------------

If you use PyOpenMensa in a project with git as source code management tool, you can add pyopenmensa via a `git submodule`__:

.. code-block:: bash

    git submodule add pyopenmensa git://github.com/mswart/pyopenmensa
    git commit pyopenmensa

The handling of git submodules is sometings tricky: e.g. submodule are not used per default. The `git book`__ describes all needed steps.

__ http://git-scm.com/docs/git-submodule
__ http://git-scm.com/book/en/Git-Tools-Submodules
