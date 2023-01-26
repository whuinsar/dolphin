# Unreleased, 0.0.2

**Added**

- Created first version of the `s1_disp_stack.py` workflow.
- Created the modules necessary for first version of the sequential workflow, including
    - `ps.py`
    - `sequential.py`
    - `io.py`
    - `interferogram.py`
    - `utils.py`
    - `unwrap.py`
    - `stitching.py`
    - `vrt.py`
- Created the `phase_link` subpackage for wrapped phase estimation.

**Changed**

**Deprecated**

**Removed**

**Fixed**

**Dependencies**

Added requirements:

- pyproj>=3.2
- tqdm>=4.60


# Unreleased, 0.0.1

**Added**

- Created the `config` module to handle the configuration of the workflows
- Command line interface for running the workflows
- Outline of project structure and utilities

**Changed**

**Deprecated**

**Removed**

**Fixed**

**Dependencies**

Added requirements:

- gdal>=3.3
- h5py>=3.6
- numba>=0.54
- numpy>=1.20
- pydantic>=1.10
- pymp-pypi>=0.4.5
- ruamel_yaml>=0.15
- scipy>=1.5

Currently, Python 3.7 is supported, but 3.11 is not due numba not yet supporting Python 3.11.