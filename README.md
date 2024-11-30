
create env
```bash
conda create -n wineq python=3.8 -y
```
activate env
``` bash
conda activate wineq
```

Create requirements.txt file and Install the Requirements
```bash
pip install -r requirements.txt
```
```bash

git init
dvc init
dvc add data_given/winequality.csv
git add .
git commit -m "first commit"
```
oneliner updates for readme

```bash
git add . && git commit -m "update README.md"
git remote add origin https://github.com/mdmehranabul/dvc-demo.git
git branch -M main
git push origin main
```