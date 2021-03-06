====
scVI
====

.. image:: https://travis-ci.org/YosefLab/scVI.svg?branch=master
    :target: https://travis-ci.org/YosefLab/scVI

.. image:: https://codecov.io/gh/YosefLab/scVI/branch/master/graph/badge.svg
  :target: https://codecov.io/gh/YosefLab/scVI

.. image:: https://readthedocs.org/projects/scvi/badge/?version=latest
        :target: https://scvi.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

Single-cell Variational Inference

* Free software: MIT license
* Documentation: https://scvi.readthedocs.io.


Quick Start
-----------

1. Install Python 3.6 or later. We typically use the Miniconda_ Python distribution.

.. _Miniconda: https://conda.io/miniconda.html

2. Install PyTorch_. If you have an Nvidia GPU, be sure to install a version of PyTorch that supports it -- scVI runs much faster with a discrete GPU.

.. _PyTorch: http://pytorch.org

3. Install scVI through pip (``pip install scvi``). We also support conda (``conda install scvi -c bioconda`` ) but due to some packaging issues of pytorch, it will force pytorch 0.4.1. Alternatively, you may download or clone this repository and run ``python setup.py install``.

4. Follow along with our Jupyter notebooks to quickly get familiar with scVI!

   a. `data loading`__
   b. `basic usage`__ 
   c. `reproducing results from the scVI paper`__ 
   d. `harmonization`__ 
   e. `annotation`__ 

.. __: https://github.com/YosefLab/scVI/tree/master/tests/notebooks/data_loading.ipynb
.. __: https://github.com/YosefLab/scVI/tree/master/tests/notebooks/basic_tutorial.ipynb
.. __: https://github.com/YosefLab/scVI/blob/master/tests/notebooks/scVI_reproducibility.ipynb
.. __: https://github.com/YosefLab/scVI/blob/master/tests/notebooks/harmonization.ipynb
.. __: https://github.com/YosefLab/scVI/blob/master/tests/notebooks/annotation.ipynb

References
----------

Romain Lopez, Jeffrey Regier, Michael Cole, Michael I. Jordan, Nir Yosef.
**"Deep generative modeling for single-cell transcriptomics."**
Nature Methods, 2018. `[pdf]`__

.. __: https://rdcu.be/bdHYQ

Chenling Xu∗, Romain Lopez∗, Edouard Mehlman∗, Jeffrey Regier, Michael I. Jordan, Nir Yosef.
**"Harmonization and Annotation of Single-cell Transcriptomics data with Deep Generative Models."**
Submitted, 2019. `[pdf]`__

.. __: https://www.biorxiv.org/content/biorxiv/early/2019/01/29/532895.full.pdf
