# 간단한 세션 구현

### 도메인
#### User

- email : 이메일
- password : 비밀번호

#### Session

- userId : 유저 아이디
- sessionKey : 세션 고유키
- inValidTime : 유효시간

### 로직
- 회원가입
    - 이메일, 비밀번호를 입력받아 회원가입
- 로그인
    - 이메일, 비밀빈호를 받아 로그인
    - 로그인시 세션키 발급
    - 동일 아이디의 세션이 3개이상 유지될 경우 세션 연결 거부