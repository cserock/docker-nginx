# Dockerfile을 이용해서 Nginx 컨테이너 + image 생성
## Docker 빌드
```
docker build -t test-nginx .
```

## Docker 실행
```
docker run -d --name test-nginx -p 8080:80 test-nginx
```

## Docker 정지
```
docker stop test-nginx
```

# Docker Compose를 실행해서 wordpress + mysql 생성
## Docker compose로 컨테이너 일괄 실행
```
docker-compose up
```
## Docker compose로 컨테이너 일괄 종료
```
docker-compose down
```