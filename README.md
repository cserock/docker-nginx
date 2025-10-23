# Dockerfile을 이용해서 Nginx 컨테이너 + image 생성
## Docker 빌드
```
docker build -t test-nginx .
```

## Docker 실행
```
docker run -d -p 8080:80 test-nginx
```

## Docker 정지
```
docker stop test-nginx
```