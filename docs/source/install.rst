Installation
============

Conda
~~~~~

``dask-ml`` is available on conda-forge and can be installed with

.. code-block:: none

   conda install -c conda-forge dask-ml

PyPI
~~~~

Wheels and a source distribution are available on PyPI and can be
installed with

.. code-block:: none

   pip install dask-ml


Optional Dependencies
---------------------

Certain modules have additional dependencies:

====================== ===========================
module                 Additional Dependencies               
====================== ===========================
``dask_ml.xgboost``    xgboost, dask-xgboost
``dask_ml.tensorflow`` tensorflow, dask-tensorflow
====================== ===========================

The conda-forge package will install all additional dependencies. With pip, the
additional dependencies are not installed by default, but can be with

.. code-block:: none

   pip install dask-ml[xgboost]    # also install xgboost and dask-xgboost
   pip install dask-ml[tensorflow]
   pip install dask-ml[complete]   # install all optional dependencies
