# Redis Monitoring
[![Build Status](https://travis-ci.org/ivandzf/redis-monitoring.svg?branch=master)](https://travis-ci.org/ivandzf/redis-monitoring)

![Home](https://github.com/ivandzf/redis-monitoring/blob/master/img/dashboard.png)

## Tech Stack
*  Vue.js
*  Springboot 1.5.14
*  Servlet Based
*  Lettuce (Redis Client)
*  Websocket (Realtime Monitoring)

## TODO
*  Memory Graph Monitoring
*  Cluster Monitoring

## Run Development
*  mvn spring-boot:run
*  cd src/main/ui
*  npm install
*  npm run dev

open in your browser -> http://localhost:8080

## Run Production
*  mvn clean package -DskipTests
*  java -jar target/redis-monitoring-1.0-SNAPSHOT.jar

open in your browser -> http://localhost:9999