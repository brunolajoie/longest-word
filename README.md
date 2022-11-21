- runtime: python38

- The runtime starts your app by running the command you specify in the entrypoint field in your app.yaml
entrypoint: gunicorn -b :$PORT main:app

App Engine will start your app with the gunicorn web server if you don't specify the entrypoint field:
- The root of your app directory contains a main.py file with a WSGI-compatible object called app.


- generate requirements.txt

- [] give api access "Permissions error fetching application [apps/ingka-data-engineering-dev]. Please make sure that you have permission to view applications on the project and that bruno@lewagon.org has the App Engine Deployer (roles/appengine.deployer) role."
