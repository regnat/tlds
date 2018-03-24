###################################################
Automatically updated list of valid TLDs for Python
###################################################

The `tlds` module provides a a set of valid TLDs directly taken from IANA_. The package is automatically updated daily.

Available on PyPI_.

.. _IANA: http://data.iana.org/TLD/tlds-alpha-by-domain.txt
.. _PyPI: https://pypi.python.org/pypi/tlds/

.. image:: https://travis-ci.org/kichik/tlds.svg?branch=master
   :target: https://travis-ci.org/kichik/tlds

.. image:: https://badge.fury.io/py/tlds.svg
    :target: https://badge.fury.io/py/tlds

Usage
-----

  >>> from tlds import tld_set
  >>> 'com' in tld_set
  True
  >>> 'foobar' in tld_set
  False
  >>> 'pizza' in tld_set
  True
  >>>