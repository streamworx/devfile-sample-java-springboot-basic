# devfile-sample-java-springboot-basic
A basic sample application using Java Spring Boot with devfile


RUN curl -Lo dd-java-agent.jar https://dtdg.co/latest-java-tracer

JAVA_OPTS_APPEND
-javaagent:/home/jboss/dd-java-agent.jar