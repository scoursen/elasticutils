.. _installation:

==============
 Installation
==============

.. Warning::

   ElasticUtils doesn't work well with ElasticSearch 0.19.9. Don't use
   that version---newer or older versions are fine.

   https://github.com/elasticsearch/elasticsearch/issues/2205
     ElasticSearch bug with ``_all``.


Requirements
============

ElasticUtils requires:

* pyelasticsearch >= 0.4


Installation
============

There are a few ways to install ElasticUtils:


From PyPI
---------

Do::

    $ pip install elasticutils


From git
--------

Do::

    $ git clone git://github.com/mozilla/elasticutils.git
    $ cd elasticutils
    $ python setup.py install
