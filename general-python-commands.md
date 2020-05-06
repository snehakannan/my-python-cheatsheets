# General Python Commands

### Creating a virtual Environment

```
cd my-project-folder
virtualenv virtualenvname
source virtualenvname/bin/activate
```

### Creating a virtual Environment with conda

Creating a virtual environment with a package numpy.

```
cd my-project-folder
conda create --name virtualenvname numpy
activate virtualenvname

deactivate

conda install pandas
```

Creating an environment with specific Python version

```
conda create --name python3venv python=3.5 numpy

activate python3venv

```

### List of all virtual environments

```
conda info --envs
lsvirtualenv 
lsvirtualenv -b
lsvirtualenv  -l
```

