Test django-ory-auth

# Run application
`python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt`

`cd core
./manage.py runserver
`
`docker-compose -f docker-compose.yml -f standalone.yml up`
