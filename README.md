# node-web-app
https://nodejs.org/ko/docs/guides/nodejs-docker-webapp/

도커라이징 tutorial

# image build
`$ docker build . -t <your username>/node-web-app`
  
# image running
`$ docker run -p 49160:8080 -d <your username>/node-web-app`
  
# 컨테이너 아이디를 확인합니다
`$ docker ps`

# 앱 로그를 출력합니다
`$ docker logs <NAMES>`
Running on http://localhost:8080

# node server running
`$ curl -i localhost:49160`
