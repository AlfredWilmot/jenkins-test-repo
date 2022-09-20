# jenkins-test-repo
This is a test repo for exploring Jenkins build automation

[Example 1](https://www.docker.com/blog/how-to-use-the-official-nginx-docker-image/): building and running an nginx container with at custom index.html
```bash
docker build -t webserver .
docker run -it --rm -d -p 8080:80 --name web webserver
```
