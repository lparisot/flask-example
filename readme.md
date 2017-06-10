A simple web application using docker and flask to understand how to use docker hub.

Sources are stored under https://gihub.com/lparisot/flask-example

Image is build using automated build under https://hub.docker.com/lparisot/flask-example

## Pull your image

```bash
$ docker pull lparisot/flask-example
```

## Run your image

```bash
$ docker run -p 8888:5000 lparisot/flask-example
```

Head over to http://localhost:8888 and the application should live.
