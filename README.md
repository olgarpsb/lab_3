# lab_3

cd lab_3
pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate
pip install -U -r requirements.txt

python3 manage.py makemigrations

python3 manage.py migrate

python3 manage.py runserver
