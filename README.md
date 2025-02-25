## Puddle - Django App  

## A web marketplace built with Django.

http://127.0.0.1:8000/


## Accessing the marketplace 
1.Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # Linux/macOS  
venv\Scripts\activate      # Windows

2.Install dependencies
pip install -r requirements.txt

3.Apply migrations
python manage.py migrate

4.Run the server
python manage.py runserver