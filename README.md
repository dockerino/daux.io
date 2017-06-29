# Daux.io Dockerfile

[![Circle CI](https://circleci.com/gh/dockerino/daux.io.png?style=badge)](https://circleci.com/gh/dockerino/daux.io)

This Dockerfile will download the latest version of daux.io and will deploy it on a apache-php container.

## Usage
````
docker pull iamwickd/daux.io
docker run -d -p 80:80 iamwickd/daux.io
````

You can now test the deployment:
````
curl http://127.0.0.1:80
// or
curl http://localhost:80
````


## TODO fix
- for some reason on Windows, opens only on accessing http://127.0.0.1/
- add htaccess to have clean urls
- add a volume for the /docs folder
- add nginx (??)
- improve documentation
