# NodeJS 어플리케이션 도커 배포
### [블로그 링크](https://hxerimione.tistory.com/6)

### 컨테이너 실행
> docker run -d -it --name node_app -v /Users/janghyerim/node-app:/app node:current-apline3.15

### 컨테이너 쉘 접속
> docker exec -it node_app /bin/sh
> 
> apline 에서는 bin/bash 지원되지않음 -> bin/sh 사용

### 서버 실행
> ssh -i <pem파일 위치>.pem ubuntu@<퍼블릭 IPv4 주소>
