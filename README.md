docker build -t test-env .

docker run -d -p 3005:8080 --name test-env-01 test-env

docker run -d -p 3005:8080 --name test-env-01 --env-file .env -v /Users/js.dev/docker/vue-env:/app  test-env