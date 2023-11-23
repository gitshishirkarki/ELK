# ELK

- docker compose up -d
- run your spring boot service
- check log in Kibana http://localhost:9200

Reuired Spring Boot dependency
implementation group: 'net.logstash.logback', name: 'logstash-logback-encoder', version: '7.2'

Required logback-spring.xml provided for Spring boot application
