# Blog Project Backend

## 기술 스택
- Java
- Spring Boot
- PostgreSQL
- JPA

---

## 프로젝트 구조

```plaintext
demo
 ├── blog
 │    ├── controller
 │    ├── domain
 │    ├── dto
 │    │    └── LoginCommandDtos.java
 │    ├── exception
 │    │    ├── LoginErrorCode.java
 │    │    └── LoginException.java
 │    ├── repository
 │    └── service
 └── exception
      ├── ApiError.java
      ├── CustomException.java
      ├── ErrorCode.java
      └── GlobalException.java
