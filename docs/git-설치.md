# git 2.9.5 설치

1. 의존성 라이브러리
```sh
   yum -y install curl-devel
   yum -y install expat-devel
   yum -y install gettext-devel
   yum -y install openssl-devel
   yum -y install zlib-devel
   yum -y install perl-devel
```

2. 다운로드
```sh
   wget --no-check-certificate https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.9.5.tar.gz
```

3. 압축 풀기
```sh
  tar xvfz git-2.9.5.tar.gz
```

4. 소스 디렉토리 이동
```sh
  cd git-2.9.5
  pwd
```

5. configure compile & build Environment
```sh
   ./configure --prefix=/usr/local/douzone2021/git
```

6. 빌드
```sh
  make all doc html info
```
   
7. 설치
```sh
   make install install-doc install-html install-info

8. 설정(/etc/profile)
```sh
   git
   PATH=$PATH:/usr/local/douzone2021/git/bin
```

9. git 환경 설정
```sh
   git config --global user.name "douzone-busan-bitacademy"
   git config --global user.email "douzone.busan.bitacademy@gmail.com"
```

10. git 사용하기
```sh
   mkdir centos-practices
   cd centos-practices
   git init
   git add -A
   git commit -m "first commit"
   git remote add origin https://github.com/douzone-busan-bitacademy/centos-practices.git
   git push -u origin master
```
================
```sh
   git add -A
   git commit -m "...."
   git push
```


=========================================================


# git clone https://github.com/douzone-busan-bitacademy/javastudy.git
# cd javastudy
# mvn clean package










  







