## 23-12-08
- [x] #10 - api versioning
- [x] #11 - 현재 로그인 한 회원의 정보를 보여주기 위해서 member/me 엔드포인트 개발
- [x] #12 - member/me 에 대한 TC 추가
- [x] #13 - CustomUserDetailsService 추가
- [x] #14 - 요청 헤더 Authorization 키에 accessToken 포함 시 자동 로그인
- [x] #15 - JwtAuthorizationFilter에서 username 대신 id로 조회하도록 변경
- [x] #16 - SpringDoc으로 API 설명 문서 자동 작성
- [x] #17 - 스웨거 로그인 기능 구현
- [x] #18 - 스프링, 스프링 시큐리티 인증 에러 메시지 커스터마이징
- [x] #19 - 게시물 조회
- [x] #20 - default_batch_fetch_size 로 N + 1 문제 해결
- [x] #21 - 게시물 단건조회
- [x] #22 - 스프링 시큐리티에서 로그인 필요없는 URL 지정시에 HTTP Method 도 지정, 더욱 더 정교하게 허용

## 23-12-01
- [x] #8 - RsData, Response 클래스 도입해서 응답 규격화
- [x] #9 - 응답 헤더에서 accessToken 삭제

## 23-11-29
- [x] #1 - 프로젝트 세팅
- [x] #2 - DB, application.yml 생성
- [x] #3 - POST /member/login 작동
- [x] #4 - 필요없는 spring security 설정 제거
- [x] #5 - NotProd에 의해서 앱 시작시에 회원 2명이 자동으로 생성
- [x] #6 - 아이디와 비번으로 로그인 시도를 하면 토큰을 받아야 한다
- [x] #7 - JwtProvider에 의해서 토큰 생성

