# deploy-detect-mt-documents

## Run web app locally:

1. Go to the application folder
```
cd deploy-detect-mt-documents
```

2. Create a virtual environment for the app
```
python -m venv venv
```

3. Activate the environment (Windows)
```
venv\Scripts\activate
```

3. Activate the environment (Linux/OSX)
```
. venv/bin/activate
```

4. Install Requirements
```
pip install -r requirements.txt
```

5. Run flask app (Windows)
```
set FLASK_APP=app.py
flask run
```

5. Run flask app (Linux/OSX)
```
export FLASK_APP=app
flask run
```
