### build command
```
$ cd /your/path/flask_demo
$ docker build -t 'flask_demo' .
```
### run command
```
$ docker run -d -p 5000:5000 flask_demo:latest
```

### test
```
$ curl 127.0.0.1:5000
```

