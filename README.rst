========
HotQueue
========
|PyPI|

    **IMPORTANT NOTE:** This project has not been actively maintained in a long time! You probably want to consider something like the Disque Redis module instead: https://github.com/antirez/disque

HotQueue is a Python library that allows you to use `Redis <http://code.google.com/p/redis/>`_ as a message queue within your Python programs.

The main advantage of this model is that there is no queue server to run, other than Redis. This is particularly ideal if you're already using Redis as a datastore elsewhere. To install it, run::

    pip install -U hotqueue

The best place to get started is `the documentation <http://richardhenry.github.com/hotqueue/>`_.

The source code is available on `GitHub <http://github.com/richardhenry/hotqueue>`_.

To get help with HotQueue, use the `HotQueue Users mailing list
<http://groups.google.com/group/hotqueue-users>`_.

Contributing
============
The source is available on `GitHub <http://github.com/richardhenry/hotqueue>`_. To contribute to the project, fork it on GitHub and send a pull request, all contributions and suggestions are welcome.

.. _PyPI: https://pypi.python.org/pypi/hotqueue

.. |PyPI| image:: https://img.shields.io/pypi/v/hotqueue.svg?style=flat
   :target: PyPI_
