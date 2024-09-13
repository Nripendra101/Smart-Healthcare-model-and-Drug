
Technologies used:
Download Anaconda from Anacond Archieve (https://repo.anaconda.com/archive/): Below is the exactly link we used 
https://repo.anaconda.com/archive/Anaconda3-2024.02-1-Windows-x86_64.exe

Download DBBrowser for SQLITE database
https://sqlitebrowser.org/dl/


asgiref
Django
joblib 
numpy 
pillow 
scikit-learn  
scipy
sqlparse
threadpoolctl  
typing_extensions
tzdata

NOTE: Make sure your Anacond has sckit-learn (To see this, open anaconda prompt then pip list to see the list of packages)

# Quick Way To Run project
Open CMD/cterminal then clone the repository, 

then create Python virtual environment 
# python -m venv venv 
then change directory to system 
# cd system 
then activate virtual environment 
# ./venv/scripts/activate
after that install project dependecies
# pip install -r requirements.txt
make migration 
# python manage.py makemigrations 
# python manage.py migrate 
then start the Django server
# python manage.py runserver 

To login as patient (username: patient and password=patient)  
To login as doctor (username: doctor and password=doctor)  
