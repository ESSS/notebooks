
.. image:: https://mybinder.org/badge_logo.svg
   :target: https://mybinder.org/v2/gh/ESSS/notebooks/master

notebooks
=========

This repo contains notebooks that explaining some cool stuff we learn every now and then.

Index
-----

* `Bounding Velocities <continuous_transition.ipynb>`_: no description.
* `Creating block matrix structures using numpy and scipy <block_matrix_with_kron_product.ipynb>`_: This notebook intends to provide a consistent way to create a block matrix structure from a simplified non-block matrix structure..
* `Einstein Summation <einsum-notebook.ipynb>`_: Einstein Summation.
* `Interpolate point cloud into structured grid <interpolation_to_a_structured_grid_from_a_cloud_of_points.ipynb>`_: Interpolate point cloud into structured grid.
* `Smooth transition between analytic functions <smooth_transition_between_analytic_functions.ipynb>`_: Create a smooth transition in a place where a function is discontinuous.
* `Test Write Strategy <test_write_strategy.ipynb>`_: A simple test that emulates a simulation loop and write raw numpy data and an HDF5 file to compare sizes and times to output a large amount of data.
* `Accumulative Sum Benchmark <accumulative_sum_benchmark.ipynb>`_: a comparison between different implementations to deal with accumulative sum using Python native loops, numpy.cumsum and sci20 Array.
* `Eigen Broadcast Cheatsheet <eigen_broadcast_cheatsheet_(cpp).ipynb>`_: examples of how to do some not-so-simple broadcasting using Eigen. Check accompanying `Numpy version <eigen_broadcast_cheatsheet_(python).ipynb>`_.

How to run
----------

1. Install `miniconda`
2. Install `nbformat` in the root environment: `conda install -n root nbformat`
3. Create an environment to run `jupyter notebook`: type `conda env create` in the root directory of this project (or `conda env update` if the `notebooks` environment was already created previously)
4. Activate the environment: type `activate notebooks` (Windows) or `source activate notebooks` (Unix)
5. Run and open it: `jupyter notebook`
