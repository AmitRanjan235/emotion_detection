commads used in this project
conda env list
mkdir utils
touch requirements.txt
touch runtime.txt
conda create -n emotion python==3.8.10 -y
conda activate emotion
conda deactivate emotion
pip install -r requirements.txt
pip freeze > requirements.txt
pip install -r runtime.txt # you can used this command or it will be directly installed by conda env creation command with python version.


for running the project:
step 1:
 first create environment using conda or pipenv or any other virtual environment creator
 step 2:
 activate the environment
 step 3:
 install the dependencies