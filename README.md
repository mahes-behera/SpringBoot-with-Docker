# SpringBoot-with-Docker
Spring boot - deployment in docker command

C:\WINDOWS\system32>CD C:\Projects\dockerTest
C:\Projects\dockerTest>docker build -t spring-boot-docker.jar .

C:\Projects\dockerTest>docker image ls -a

spring-boot-docker.jar   latest              079b8c2b3a01        4 minutes ago       543 MB

C:\Projects\dockerTest>docker run -p 9090:8081 spring-boot-docker.jar

Note- In above 9090 is docker port and 8081 is spring boot port
so If you run the above command with this url:-  http://localhost:9090/message
you can run browser.
