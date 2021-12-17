**Activate the virtual enviroment**

For MacOS and Linux / Git Bash:
```
source blockchain-env/Source/activate
```
For Windows:
```
\blockchain-env\Source\activate.bat
```

**Install all packages**
```
pip3 install -r requirements.txt
```

**Run the tests**

Make sure to activate the virtual enviroment.

```
python3 -m pytest backend/tests
```

**Run the application and API**

Make sure to activate the virtual enviroment.

```
python3 -m backend.app
```

**Run a peer instance**

Make sure to activate the virtual enviroment.

For Linux / MacOS / Git Bash:
```
export PEER=True && python3 -m backend.app
```

For Windows:
```
SET PEER=True && python3 -m backend.app
```

**Run the frontend**

In the frontend directory:
```
npm run start
```

**Seed the Backend with data**

Make sure to activate the virtual enviroment.

For Windows:
```
set SEED_DATA=True
python3 -m backend.app
```
For Linux / MacOS:
```
export SEED_DATA=True && python3 -m backend.app
```