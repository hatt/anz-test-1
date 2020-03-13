# ANZx Technical Test 1

This Dockerfile builds a container with a webservice on HTTP port 8000.


## Build

```
docker build -t anzxtest1:v1.0.0 .
```


## Run

```
docker run -p 8000:8000 anzxtest:v1.0.0
```


## Test

```
curl http://localhost:8000
```

Expected output:
```
Hello, world.
```
