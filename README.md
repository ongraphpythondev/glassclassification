# glassclassification
<br><h1>Prerequisites:</h1><br>
You will need the following programmes properly installed on your computer.<br>
Python 3.7+ <br>
django 2.2+ <br>
Virtual Environment
To install virtual environment on your system use:

pip install virtualenv

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


objective: Its Based on Machine Learning app to classify the glass category and uses based on Given Input<br>
(Attribute Information:<br>
RI: refractive index<br>
Na: Sodium (unit measurement: weight percent in corresponding oxide, as are attributes 4-10)<br>
Mg: Magnesium<br>
Al: Aluminum<br>
Si: Silicon<br>
K: Potassium<br>
Ca: Calcium<br>
Ba: Barium<br>
Fe: Iron<br>
Type of glass: (class attribute)<br>
-- 1 buildingwindowsfloatprocessed<br>
-- 2 buildingwindowsnonfloatprocessed<br>
-- 3 vehiclewindowsfloatprocessed<br>
-- 4 vehiclewindowsnonfloatprocessed (none in this database)<br>
-- 5 containers<br>
-- 6 tableware<br>
-- 7 headlamps<br>
)
