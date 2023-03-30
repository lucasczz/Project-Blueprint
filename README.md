# Project-Blueprint

This repository provides an exemplary blueprint (based on the blog post at [neptune.ai](https://neptune.ai/blog/how-to-organize-deep-learning-projects-best-practices) for the file structure of a machine learning project, which is intended to be populated as follows but can of course be freely adapted to fit your needs:

| Directory  | Intended Contents                                                |
|------------|------------------------------------------------------------------|
| data       | Datasets                                                         |
| models     | Model parameters, checkpoints etc.                               |
| notebooks  | Jupyter notebooks used e.g. for data exploration or prototyping  |
| reports    | Experimental results, training logs, data visualizations         |
| src/data   | Data handlers, -generators etc.                                  |
| src/models | Model implementations                                            |
| tools      | Experiment scripts                                               |

To use the blueprint, perform the following steps: 
1. Either download the project as a .zip file or create a fork.
2. Replace this README.md with one that describes your project.
3. Fill out the name, and version of your project in `setup.py`. 
4. Add your Python dependencies to `requirements.txt`.
5. Create a Python environment for your project using `conda env create -n ENVNAME --file environment.yml` or alternatively use virtualenv.
6. Activate your environment using `conda activate ENVNAME` and start developing. 
