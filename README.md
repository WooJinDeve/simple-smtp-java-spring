### 개요
스프링 `SMTP`를 이용한, 회원가입 이메일 인증코드 로직입니다.

### 스프링 SMTP 

**application.properties**
``` yaml
spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=<email>
spring.mail.password=<password>
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
```
**application.yml**
``` yaml
spring:
  mail:
    host: smtp.gmail.com
    port: 587
    username: <email>
    password: <password>
    properties:
      mail:
        smtp:
          auth: ture
          starttls:
            enable: true
```

### 참고
[스프링 STMP 도입하기](https://sokdak-sokdak.tistory.com/3)
