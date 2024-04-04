# Nginx
Nginx는 가벼움과 높은 성능, 안전화를 목표로 만들어진 오픈소스 웹 서버 이다.

## 1. 주요 기능 및 특징
* HTTP, TCP나 UDP 요청을 받아 정적인 컨텐츠를 제공
* WAS를 거치지 않고 컨텐츠를 제공할 수 있으며, Caching을 통해 성능 향상
* Proxy로써, 이메일 서버 혹은 리버스 프록시의 역할을 하여 타 서버와 연결 가능
* Load Balancer의 역할로 트래픽 분산 

## 2. 설  치

### 2-1. Ubuntu 환경
|구분|버전|빌드|
|------|---|---|
|Ubuntu|22.04.2|-|
|Nginx|1.24.1|-|

위 버전을 기준으로 Ubuntu 환경에서 Install 하였습니다. <br>
nginx, pcre, zlib, openssl Source 파일을 압축하여 Release에 Update 하였습니다. <br>

**1. 서버에서 다운로드**
```
 $ wget https://github.com/SungHwan-Jo/Nginx/releases/download/Nginx-1.25.1/nginx-1.25.1.tar.gz
```

**2. 다운로드 후 압축 해제**
```
 $ tar -zxvf nginx-1.25.1.tar.gz
```

**3. install_guid.sh 실행** <br>
압축해제한 디렉토리 내에서 install_guid.sh 실행 하여 설치 절차 참고하여 진행
