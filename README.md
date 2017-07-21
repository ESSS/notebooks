# notebooks

This repo contains notebooks that explaining some cool stuff we learn every now and then.

# Index

* [Bounding Velocities](continuous_transition.ipynb): no description.
* [Creating block matrix structures using numpy and scipy](block_matrix_with_kron_product.ipynb): This notebook intends to provide a consistent way to create a block matrix structure from a simplified non-block matrix structure..
* [Einstein Summation](einsum-notebook.ipynb): Einstein Summation.
* [Interpolate point cloud into structured grid](interpolation_to_a_structured_grid_from_a_cloud_of_points.ipynb): Interpolate point cloud into structured grid.
* [Smooth transition between analytic functions](smooth_transition_between_analytic_functions.ipynb): Create a smooth transition in a place where a function is discontinuous.

## How to run

1. Install `miniconda`
2. Install `nbformat` in the root environment: `conda install -n root nbformat`
2. Create an environment to run `jupyter notebook`: type `conda env create` in the root directory of this project (or `conda env update` if the `notebooks` environment was already created previously)
3. Activate the environment: type `activate notebooks` (Windows) or `source activate notebooks` (Unix)
4. Run and open it: `jupyter notebook`
