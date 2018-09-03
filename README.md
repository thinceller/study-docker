# study-docker
study Udemy lesson and 「Docker/Kubernetes 実践コンテナ開発入門」
## Lesson Video
https://www.udemy.com/docker-k/learn/v4/overview

## Book
http://amzn.asia/d/1P1lgGD

### test-nginx
```
$ cd test-nginx
$ docker run --name test-nginx \
-v /Users/kohei/github/study-docker/test-nginx/html:/usr/share/nginx/html:ro \
 -d -p 8080:80 nginx
 ```
