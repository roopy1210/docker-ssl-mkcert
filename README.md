# 로컬 환경에서 Docker Conmpose와 mkcert를 이용하여 https 개발환경 만들기

# Installation
### *1.choco 설치하기*
https://chocolatey.org/install 에서 Now run the following command: 부분 명령어 복사하여서 터미널에서 실행

### *2.mkcert 설치하기*
choco install mkcert

### *3.인증서 생성하기*
mkcert -install
mkcert localhost

### *4.docker-compose.yml 작성하기*

### *5.nginx.conf 작성하기*

### *6.docker-compose.yml 실행하기*
docker-compose up -d

