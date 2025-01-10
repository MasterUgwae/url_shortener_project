### Running
Windows: 
```
python -m venv venv
.\venv\Scripts\activate
```
Linux/MacOS:
```
python3 -m venv venv
source venv/bin/activate
```

All OS:
```
python -m pip install fastapi==0.75.0 uvicorn==0.17.6
python -m pip install sqlalchemy==1.4.32
python -m pip install python-dotenv==0.19.2
python -m pip install validators==0.18.2
uvicorn shortener_app.main:app --reload
```
