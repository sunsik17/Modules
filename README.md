### 멀티모듈

- "module-admin": 관리자 서버 모듈로, 관리자와 관련된 기능을 담당합니다.
- "module-user": 사용자 서버 모듈로, 사용자와 관련된 기능을 담당합니다.
- "module-client": 네트워크로 연결된 서버로부터 정보를 제공받는 모듈입니다. 이 모듈에는 "mailgun-client"와 같은 하위 모듈이 존재할 수 있으며, 이 모듈을 통해 외부 서버와의 통신을 처리합니다.
- "module-common": 공통된 코드를 작성하는 모듈로, 엔티티(entity)나 레포지토리(repository) 등을 포함할 수 있습니다.
---

### 개선해야할 점

- 해당 모형의 아키텍처는 완성된 것이 아닙니다.
- User 나 Admin Application도 하나로 둘 것이 아니라 관심사나 역할에 따라 모듈을 세부적으로 분리해야합니다.
- common의 영역이 비대해지는 문제가 발생합니다.
  
### 아키텍처

![제목 없는 다이어그램 drawio (2)](https://github.com/sunsik17/Modules/assets/117346927/d6a9ee65-671c-4ad6-8825-29165957df69)
