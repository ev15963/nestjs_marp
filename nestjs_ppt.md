---
marp: true
theme: gaia # 커스텀테마
class: invert # 다크모드 전환
paginate: true
---

<!-- _class: title -->

![bg right:40% 80%](static/nestjs_image.png)
# NestJS 세미나

###### 작성자
###### 작성일자 23.07.23.

---

# 목차

- nest란?
- express, fastify vs nestjs
- typescript
- 장점

---
# 다음페이지

```markdown
# Slide 1

foobar

---
# Slide 2

foobar
```

---

# 장점
1. swagger api 어노테이션 기능으로 자동 생성
2. typescript를 기본으로 채택하여 타입오류를 잡을 수 있음
3. nest-cli로 `module - controller - service`의 기본 골자를 제공 받을 수 있음
4. 확장성이 좋다.
4.1. Nest 자체에 붙어있는 것이라 호환성 문제가 없음
4.2. 라이브러리가 자체적으로 지원 (GraphQL, Mongoose, TypeORM, Elasticsearch 등)
![10% 10%](static/www.npmjs.com_search_q=nestjs%252F.png)
5. 유효성 검사
---
# 출처

https://velog.io/@leo3179/Nest.js-%EB%A6%AC%EB%B7%B0

https://www.npmjs.com/search?q=nestjs%2F

flowchart LR
    A[구매] --> B;
    B[유저, 파라미터, \n 어뷰징 검증] --> C;
    C{client가 안드로이드} -->|Yes| E;
    C -->|No| G;
    E[안드로이드 Proxy 처리] --> G;
    G[DB 저장] --> I;
    I[응답 반환];