FROM openjdk:9.0.1-11-jdk-slim

COPY polling-agent.jar /polling-agent.jar
COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]