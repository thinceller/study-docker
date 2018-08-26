# study-docker
## Lesson Video
https://www.udemy.com/docker-k/learn/v4/overview

## test-nginx
```
$ docker run --name test-nginx \
-v /Users/kohei/github/study-docker/test-nginx/html:/usr/share/nginx/html:ro \
 -d -p 8080:80 nginx```
