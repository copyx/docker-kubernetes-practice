# 1. node 설치
FROM node:12-alpine

# 3. 패키지 설치
WORKDIR /usr/src/app
RUN npm install

# 2. 소스 복사
COPY . /usr/src/app

# 4. 실행
EXPOSE 3000
CMD node server.js