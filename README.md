# 도커 + 마라톤 치트키!!!!!!!!!!! 항상 까먹을수 밖에 없다!!! 우워어어엉!!

#### 1) 도커 실행 관련 확인 명령어
도커버전 확인:
```sh
$ docker version
```

도커 관련 정보 확인:
```sh
$ docker info
```

도커 컨테이너 목록 확인:
```sh
$ docker ps -a
```
도커 이미지 목록 확인:
```sh
$ docker images
```
#### 도커헙 관련 명령어
도커헙로그인: 이미지를 도커헙에 푸시 하기 위해서 로그인 해줘야 한다.
```sh
$ docker login [도커헙주소 ex> hub.docker.com]
```
도커헙로그아웃: 다른 도커헙을 이용하기 위해서 로그아웃이 필요할 때가 있다.
```sh
$ docker logout [도커헙주소 ex> hub.docker.com]
```
