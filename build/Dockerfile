FROM java:8
VOLUME /tmp
<<<<<<< HEAD
ADD openshift-spring-0.4.0.jar openshift-spring-0.4.0.jar
# RUN curl -sf -o /opt/jenkins-1.523.war -L http://mirrors.jenkins-ci.org/war/1.523/jenkins.war
RUN bash -c 'touch /openshift-spring-0.4.0.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/openshift-spring-0.4.0.jar"]
=======
ADD openshift-spring-0.1.0.jar openshift-spring-0.1.0.jar
# RUN curl -sf -o /opt/jenkins-1.523.war -L http://mirrors.jenkins-ci.org/war/1.523/jenkins.war
RUN bash -c 'touch /openshift-spring-0.1.0.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/openshift-spring-0.1.0.jar"]
>>>>>>> 2808e2227e0602dda2fbabba279cd8993d85e68b
expose 8080
