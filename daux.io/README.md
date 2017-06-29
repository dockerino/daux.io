# Daux.io Dockerfile

This Dockerfile will download the latest version of daux.io and will deploy it on a apache-php container.

## Usage
````
docker pull iamwickd/daux.io
docker run -d -p 72:72 iamwickd/daux.io
````

You can now test the deployment:
````
curl http://localhost:72
````


## TODO fix
- add htaccess to have clean urls
- add a volume for the /docs folder
- add nginx (??)
- improve documentation
