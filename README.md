Minimal docker curl image

build

docker build -f curl.docker -t curl-docker .

execute a curl

docker run curl-docker http://localhost
