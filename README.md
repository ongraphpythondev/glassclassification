# glassclassification
<br><h1>Prerequisites:</h1><br><br>
You will need the following programmes properly installed on your computer.<br>
Python 3.7+ <br>
django 2.2+ <br>
Virtual Environment
To install virtual environment on your system use:

pip install virtualenv <br>

or<br>

pip3 install virtualenv #if using linux(for python 3 and above) <br>

<br><h1>Installation and Running :</h1><br><br>
git clone https://github.com/ongraphpythondev/glassclassification.git <br>
cd glassclassification<br>

virtualenv venv or virtualenv venv -p python3 #if using linux(for python 3 and above)

venv\Scripts\activate # for windows or source venv/bin/activate # for linux

<br><h1>install required packages for the project to run</h1>
pip install -r requirements.txt

python manage.py runserver

<h1>Test Url at local system</h1>
http://127.0.0.1:8000


objective: Its Based on Machine Learning app to classify the glass category and uses based on Given Input
(Attribute Information:
RI: refractive index
Na: Sodium (unit measurement: weight percent in corresponding oxide, as are attributes 4-10)
Mg: Magnesium
Al: Aluminum
Si: Silicon
K: Potassium
Ca: Calcium
Ba: Barium
Fe: Iron
Type of glass: (class attribute)
-- 1 buildingwindowsfloatprocessed
-- 2 buildingwindowsnonfloatprocessed
-- 3 vehiclewindowsfloatprocessed
-- 4 vehiclewindowsnonfloatprocessed (none in this database)
-- 5 containers
-- 6 tableware
-- 7 headlamps
)
