# How to run

1. Build the image:
```sh
docker build --tag task0 .
```

2. Run the test
```sh
docker run --rm -v "$(pwd):/results" task0
```
