# CardeaCodingAssessment

steps to recreate:

clone the repository

decrompress the zip, and then decompress the zip within 

cd to the frontend and install node modules

npm start and it should be active without the data

To start the backend:

open a new terminal window and cd to the backend

Do the following commands:

python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
python manage.py loaddata db.json
python manage.py runserver

^if that doesn't work try migrating it and then running but you should not have to.
