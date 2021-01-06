## Initialization
Set up virtual environment:

```
python3 -m venv venv                # creates venv directory
. venv/bin/activate                 # changes prompt
pip install -r requirements.txt     # installs requirements in the venv directory
```

After running ```venv/bin/activate``` one can execute ```deactivate``` to revert to original environment.

## Running
Use ```run_uwsgi``` if you have uwsgi installed, otherwise use ```run_flask.sh```. Both run in development environment by default, can change to production if given "prod" as an argument.

App listens on localhost on default port of 5000.

## DB model
The database description can be found in ```doc/makethempay.dbm```. It can be opened in pgModeler.
