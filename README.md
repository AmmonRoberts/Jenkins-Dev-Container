
docker build -t jenkinstest .

docker run -p 8080:8080 --rm jenkinstest