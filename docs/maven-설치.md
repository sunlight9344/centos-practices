## Maven 3.8.1 설치

1. 다운로드
```sh
# wget https://mirror.navercorp.com/apache/maven/maven-3/3.8.1/binaries/apache-maven-3.8.1-bin.tar.gz
```

2. 압축 풀기
```sh
# tar xvfz apache-maven-3.8.1-bin.tar.gz
```

3. 설치
```sh
mv /root/apache-maven-3.8.1 /usr/local/poscodx2023/maven3.8
ln -s /usr/local/poscodx2023/maven3.8 /usr/local/poscodx2023/maven
```

4. 설정(/etc/profile)
```sh
export PATH=$PATH:/usr/local/douzone2021/maven/bin
 ```
