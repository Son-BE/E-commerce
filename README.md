# 개요
쇼핑몰 프로젝트

Use : Spring, Jpa, Mysql, Redis, Docker, AWS,

Goal : 판매자와 구매자 사이를 중개 해주는 커머스 서버 구축

## 회원
### 공통
  - [ ] 이메일을 통한 인증번호를 통한 회원 가입 // 소셜미디어 추가 예정
### 고객
  - [ ]  회원 가입
  - [ ]  인증 시스템(이메일)
  - [ ]  로그인 토큰 발행
  - [ ]  로그인 토큰을 통한 제어확인 { JWT,Filter를 사용해서 간략하게}
  - [ ]  예치금 관리


### 셀러
  - [ ]  회원 가입
  
## 주문 서버

### 셀러
  - [ ] 상품등록, 수정
  - [ ] 상품 삭제    

### 구매자
  - [ ] 장바구니를 위한 Redis 연동
  - [ ] 상품 검색 & 상세 페이지
  - [ ] 장바구니에  물건 추가
  - [ ] 장바구니 확인
  - [ ] 주문하기
  - [ ] 주문 내역 이메일로 발송하기

## 주문
  - [ ]   장바구니
  - [ ]   고객이 주문
