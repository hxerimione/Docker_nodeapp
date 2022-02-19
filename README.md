### 컨테이너 실행
> docker run -d -it --name node_app -v /Users/janghyerim/node-app:/app node:current-apline3.15

### 컨테이너 쉘 접속
> docker exec -it node_app /bin/sh
> apline 에서는 bin/bash 지원되지않음 -> bin/sh 사용