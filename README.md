#To create Python3.7 virtual environment

python3.7 -m virtualenv MyEnv

#To enter virtual environment of python 3.7

source MyEnv/bin/activate


#To install Jupyternotebook in virtual Environment

ipython kernel install --user --name MyEnv --display-name "Python 3.7"

#To run Jupyternotebook

jupyter notebook

#To run DJango Project

pip install -r requirements.txt
python ./manage.py migrate
python ./manage.py createsuperuser
python ./manage.py runserver

#To run Flask Project

cd dir/app/
export FLASK_APP=model.py
flask run
