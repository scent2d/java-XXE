# java-XXE
Test XXE


# 환경구성
cd xxe
mvn package
docker-compose up -d

# 취약점 테스트
http://[IP]:8888/XXE/insecure
http://[IP]:8888/XXE/secure

- Upload users.xml
- Upload malicious-xml.xml

