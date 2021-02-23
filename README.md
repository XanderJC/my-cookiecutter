# Machine Learning Project Cookiecutter

This cookiecutter provides a quick and easy way to create new ML projects. 
It was inspired by [Cookiecutter DataScience](https://drivendata.github.io/cookiecutter-data-science/) and is a lightly edited fork of the [AI4ER Cookiecutter](https://github.com/ai4er-cdt/ai4er-cookiecutter).

The current version automatically sets up:
1. A useful folderstructure for notebooks, source code, documentation, etc.
2. Automatically create a symlink to your data folder for easy and unified data access.
3. Automatically initialize as github repo and link to an existing (empty!) repository on github.com
4. Automatically create a new conda environment for your project and store it in the projects `/env` subdirectory. 

## Usage

Make sure that you have a working version of `python` (>= 3.0) and `cookiecutter` (>=1.7) installed via

```pip install --user cookiecutter```
 or 
```conda install cookiecutter```

For more information on the installation of cookiecutter, see [here](https://cookiecutter.readthedocs.io/en/1.7.2/installation.html).

To use this cookiecutter, you simply type the following into your command line:
> ```cookiecutter https://github.com/XanderJC/my-cookiecutter.git``` 

The cookiecutter will then automatically prompt you to set project names, etc.
