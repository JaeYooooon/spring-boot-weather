## 📍 Account Project
하루의 날씨와 일기를 기록하는 날씨 일기 프로젝트

## ⚙ Tech Stack
- Language : Java
- Build : Gradle 
- Framework : Spring Boot 2.7.11
- JDK : JDK 1.8
- Database : MySQL

## 🔌 Dependencies
- Spring JPA
- Spring Web
- MySQL Connector
- Lombok
- Swagger
- Json Simple

## 🛠 Function
**Function**                 | **구현 완료** | 
:--------------------------  | :----------------: |  
**Open API 활용 데이터 호출/파싱/저장**   | :heavy_check_mark: | 
**날씨 데이터 조회/수정/삭제**            | :heavy_check_mark: |
**logback 활용 로그 기록**                | :heavy_check_mark: |
**Spring Scheduler 활용 API 호출 최소화** | :heavy_check_mark: | 
**Swagger 활용 API Document 작성**        | :heavy_check_mark: | 

## 🔻 RestAPI EndPoint
| **Method Type** | **URI** | **Function** | **Parameter** |
| ------ | ------------- | -------------- |---------------- | 
| POST   | /create/diary | 일기 생성      | 날짜, 일기 텍스트 |
| GET    | /read/diary   | 일기 조회      | 날짜             |
| GET    | /read/diaries | 일기 목록 조회 | 날짜 기간         |
| PUT    | /update/diary | 일기 수정      | 날짜, 일기 텍스트 | 
| DELETE | /delete/diary | 일기 삭제      | 날짜             |

## ❗ Impression
이번 프로젝트에서는 스케쥴링, 로그, swagger 등 다양한 내용을 배워서 좋았다. 또한 GlobalException 을 통한 전역 예외처리를 사용 해 볼 수 있어서 도움이 됐다. 나중에 팀프로젝트를 진행을 하게되면 swagger를 활용해보고싶다.
