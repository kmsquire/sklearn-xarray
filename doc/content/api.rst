API Reference
=============

.. _API/Wrappers:

Wrappers
--------

.. py:currentmodule:: sklearn_xarray

Module: :py:mod:`sklearn_xarray`

.. autosummary::
    :nosignatures:

    wrap
    ClassifierWrapper
    RegressorWrapper
    TransformerWrapper

DataArray wrappers
------------------

Module: :py:mod:`sklearn_xarray.dataarray`

.. warning::
    This module has been deprecated in favor of the more flexible top-level
    functions and classes (see :ref:`API/Wrappers`).


Dataset wrappers
----------------

Module: :py:mod:`sklearn_xarray.dataset`

.. warning::
    This module has been deprecated in favor of the more flexible top-level
    functions and classes (see :ref:`API/Wrappers`).


Target
------

.. py:currentmodule:: sklearn_xarray

Module: :py:mod:`sklearn_xarray`

.. autosummary::
    :nosignatures:

    Target

.. _API/Pre-processing:

Pre-processing
--------------

.. py:currentmodule:: sklearn_xarray.preprocessing

Module: :py:mod:`sklearn_xarray.preprocessing`

Object interface:

.. autosummary::
    :nosignatures:

    Concatenator
    Featurizer
    Reducer
    Resampler
    Sanitizer
    Segmenter
    Splitter
    Transposer


Functional interface:

.. autosummary::
    :nosignatures:

    concatenate
    featurize
    preprocess
    reduce
    resample
    sanitize
    segment
    split
    transpose


Model selection
---------------

.. py:currentmodule:: sklearn_xarray.model_selection

Module: :py:mod:`sklearn_xarray.model_selection`

.. autosummary::
    :nosignatures:

    CrossValidatorWrapper


Utility functions
-----------------

.. py:currentmodule:: sklearn_xarray.utils

Module: :py:mod:`sklearn_xarray.utils`

.. autosummary::
    :nosignatures:

    convert_to_ndarray
    get_group_indices
    segment_array
    is_dataarray
    is_dataset
    is_target


Datasets
--------

.. py:currentmodule:: sklearn_xarray.datasets

Module: :py:mod:`sklearn_xarray.datasets`

.. autosummary::
    :nosignatures:

    load_dummy_dataarray
    load_dummy_dataset
    load_digits_dataarray
    load_wisdm_dataarray

Data
----

Module: :py:mod:`sklearn_xarray.data`

.. warning::
    This module has been deprecated in favor of the
    :py:mod:`sklearn_xarray.datasets` module.


List of modules
---------------

    .. toctree::

        api/common
        api/preprocessing
        api/model_selection
        api/utils
        api/datasets
