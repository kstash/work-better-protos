# WorkBetter gRPC protocols

마이크로서비스간 통신 규격으로 gRPC를 사용하고, proto 파일 문법은 `proto3` 사용한다.

### user.proto

---

OAuth로 회원가입하려고 할 때, 사용자 email이 이미 존재하는지 확인하기 위한 용도로 `auth-service` &rarr; `user-service` **email** 값을 전달한 뒤, **exists** 값을 받는다.
