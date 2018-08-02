Follow the instructions to get asciiflow running locally.

Compile the javascript:
```
$ ./compile.sh
```

If you get a permissions error:
```
$ chmod a+x closure-compiler.jar
```

Run a simple web server:
```
$python -m SimpleHTTPServer
```

Goto: http://localhost:8000/index.html

Run in a docker
```
$ sudo docker run -d --rm --name asciiflow -v `realpath $PWD`:/webapp -p 8080:8080 panguolin/webapp
```
