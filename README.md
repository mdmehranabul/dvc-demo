create env

'''bash
conda create -n wineq python=3.8 -y
'''bash

activate env
'''bash
conda activate wineq
'''bash

create requirements.txt file
install the requirements
'''bash
pip install -r requirements.txt
'''bash

git init
dvc init
dvc add data_given/winequality.csv
