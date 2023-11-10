# dvc-project-template
DVC project template

## Reference Repo
[Official reference repo](https://github.com/abhishekjadhav3470/DVC_NLP)

## STEPS -

### STEP 01- Create a repository by using template repository

### STEP 02- Clone the new repository

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.7 -y
```

```bash
conda activate ./env
```
OR
```bash
source activate ./env

```
### One shot create and activate environment
```bash
conda create --prefix ./env python=3.7 -y && source activate ./env
```
### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 05- initialize the dvc project
```bash
dvc init
```

### STEP 06- commit and push the changes to the remote repository