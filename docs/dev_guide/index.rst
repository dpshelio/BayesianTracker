===============
Developer guide
===============

Installing the latest development version
-----------------------------------------

If you would rather install the latest development version, and/or
compile directly from source, you can clone and install from this repo:

.. code:: sh

   $ git clone https://github.com/quantumjot/BayesianTracker.git
   $ conda env create -f ./BayesianTracker/environment.yml
   $ conda activate btrack
   $ cd BayesianTracker
   $ pip install -e .

Addtionally, the ``build.sh`` script will download Eigen source, run the
makefile and pip install.
