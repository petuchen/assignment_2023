# Tech Assignment

---
## File & Directory

+ 01_first_task.ipynb: notebook for the 1st question (with html format for easy checking)
+ 02_second_task.ipynb: notebook for the 2nd question (with html format for easy checking)
+ sales.csv: sales data
+ presentation.html: final presentation in html format

---
## Environment

### Conda Environment

- [Create conda environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) (you can also update the environment from as described [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#updating-an-environment)):

  `conda env create -f environment.yml`

- Activate conda environment:

  `conda activate assignment_tc`

- Run [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/index.html#):

  `jupyter lab`

- Deactivate current conda environment:

  `conda deactivate`


### MLflow server

- Navigate to the folder where your code resides
- Launch a terminal and type `mlflow ui`
- Open browser and type **http://127.0.0.1:5000** or **http://localhost:5000**