jetstream
========

.. contents:: **Table of Contents**
    :backlinks: none

Installation
------------

Jetstream is distributed on `PyPI <https://pypi.org>`_ as a universal
wheel and is available on Linux/macOS and Windows and supports
Python 2.7/3.5+ and PyPy.

.. code-block:: bash

    $ pip install migrator
    
Usage
-----
.. code-block:: python

def up('model.name', lambda cr: (
    cr.add('product_id', ref="product.product', type="Integer", default=2, index=True), 
    cr.rename('product_id', "product_product_id'), 
    cr.delete(soft=True),

))
  

License
-------

migrator is distributed under the terms of both

- `MIT License <https://choosealicense.com/licenses/mit>`_
- `Apache License, Version 2.0 <https://choosealicense.com/licenses/apache-2.0>`_

at your option.
