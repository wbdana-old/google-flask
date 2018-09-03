# google-flask

## Running the test app
- Clone the repo
- Create your environment
	- On Arch: `virtualenv2 env`
- Activate your environment: `source env/bin/activate`
- Install requirements: `pip install -r requirements.txt`
- Create your credentials file using credentials from https://console.developers.google.com
- Source the credentials file and run the application: `source credentials && python app.py`
- Navigate to http://127.0.0.1:5000 and log in