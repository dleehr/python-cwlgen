.. python-cwlgen - Python library for manipulation and generation of CWL tools.

.. _install:

************
Installation
************

.. Note::
    We highly recommend the use of a virtual environment with Python 3.6.0
    using `virtualenv`_ or `conda`_.

.. _virtualenv: https://virtualenv.pypa.io/en/latest/
.. _conda: http://docs.readthedocs.io/en/latest/conda.html

.. _dependencies:

python-cwlgen dependencies
==========================

python-cwlgen is initially built with Python3 and uses the following libraries:

- ruamel.yaml (0.13.7)
- six (1.10.0)

.. _installation:

Installation procedure
======================

Pip
---

You can use pip to install the latest version from pypi:

.. code-block:: bash

    pip install cwlgen

Manually
--------

Clone the repository and install cwlgen with the following command:

.. code-block:: bash

    git clone https://github.com/common-workflow-language/python-cwlgen.git
    cd python-cwlgen
    pip install .

.. _uninstallation:

Uninstallation procedure
=========================

Pip
---

You can remove python-cwlgen with the following command:

.. code-block:: bash

    pip uninstall python-cwlgen

.. Note::
    This will not uninstall dependencies. To do so you can make use of `pip-autoremove`_.

.. _pip-autoremove: https://github.com/invl/pip-autoremove
