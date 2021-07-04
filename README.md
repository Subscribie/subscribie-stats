# Stripe Connect Connected Fees

API to show total collected fees via Stripe connect.

<img src="https://user-images.githubusercontent.com/1718624/124388884-bacf5d80-dcdc-11eb-84fa-c6ed4a825d48.png" />

# How to run locally


## Setup!

```
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
```

## Run
```
. venv/bin/activate
export STRIPE_LIVE_SECRET_KEY=secret #or test key
cd app/app/
uvicorn main:app --reload
```

# Visit api

http://127.0.0.1:8000/docs

