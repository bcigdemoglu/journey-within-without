# affirmations

Using AI's superpowers to help us in our darkest times

## Build Work Notes

Following steps on <https://tutlinks.com/create-and-deploy-fastapi-app-to-heroku/>

```bash
# Setup ptyhon and virtual env
python3 -m venv env
source ./env/bin/activate
python -m pip install --upgrade pip

# Install fast api with all reqs
pip install "fastapi[all]"

# OR install min reqs
pip install fastapi
pip install uvicorn

# To serve on heroku
pip install gunicorn

# Free all reqs
pip freeze > requirements.txt
```

## Build Setup

```bash
# Setup ptyhon and virtual env
source ./env/bin/activate
python -m pip install --upgrade pip

# Install reqs
pip install -r requirements.txt
```
