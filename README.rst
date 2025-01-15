``httplib2`` Transport for Google Auth
======================================


|pypi|

This library provides an `httplib2`_ transport for `google-auth`_.

.. note:: ``httplib`` has lots of problems such as lack of threadsafety
    and insecure usage of TLS. Using it is highly discouraged. This
    library is intended to help existing users of ``oauth2client`` migrate to
    ``google-auth``.

.. |pypi| image:: https://img.shields.io/pypi/v/google-auth-httplib2.svg
   :target: https://pypi.python.org/pypi/google-auth-httplib2

.. _httplib2: https://github.com/httplib2/httplib2
.. _google-auth: https://github.com/GoogleCloudPlatform/google-auth-library-python/


[![Deprecated](https://img.shields.io/badge/status-deprecated-red.svg)](https://github.com/httplib2/httplib2)

This project is deprecated and no longer actively maintained. 

**Reason for deprecation:**

* The library was created to provide legacy support for httplib2 to help clients migration from [oauth2client](https://github.com/googleapis/oauth2client) to [google-auth](https://github.com/googleapis/google-auth-library-python/tree/main)

**Alternatives:**

* For any new usages please see provided transport layers by [google-auth](https://github.com/googleapis/google-auth-library-python/tree/main) library.

**Important notes:**

* Existing users are encouraged to migrate to the recommended alternatives.
* No further updates, bug fixes, or security patches will be provided.


Installing
----------

You can install using `pip`_::

    $ pip install google-auth-httplib2

.. _pip: https://pip.pypa.io/en/stable/

License
-------

Apache 2.0 - See `the LICENSE`_ for more information.

.. _the LICENSE: https://github.com/GoogleCloudPlatform/google-auth-library-python/blob/main/LICENSE
