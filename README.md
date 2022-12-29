# Flask app deployment

This is a basic flask app developed while learning google Cloud Run. Cloud run enables developers to build 
and deploy applications very easily while scaling containers automatically through CI/CD.

## To test:
1. Install `virtualenv`:
```
$ pip install virtualenv
```

2. Create virtual environment:
```
$ virtualenv env
```

3. Activate the environment:
```
$ .\env\Scripts\activate
```

4. Install the dependencies:
```
$ (env) pip install -r requirements.txt
```

5. Start the web server:
```
$ (env) python app.py
```