FROM tomcat:10.1.36-jdk21

# 타임존 설정
RUN ln -sf /usr/share/zoneinfo/Asia/Seoul /etc/localtime

# WAR 파일 복사
COPY build/libs/ITS-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/ROOT.war

# Tomcat 실행
CMD ["catalina.sh", "run"]
