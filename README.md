# Run asciiflow locally

## Compile the javascript
```
$ ./compile.sh
```

## If you get a permissions error
```
$ chmod a+x closure-compiler.jar
```

## Run in web server
### python simple web server
```
$ python -m SimpleHTTPServer
```

### A docker with web server
```
$ sudo docker run -d --rm --name asciiflow -v `realpath $PWD`:/webapp -p 8000:8080 panguolin/webapp
```

# Goto web page
```
http://localhost:8000
```
