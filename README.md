# SpringBoot JPA 활용1

## 1. 도메인 분석 설계(Done)

    도메인 모델 설명과 테이블 설계
    엔티티를 어떻게 개발을 해야 하며 엔티티를 설계할 때 주의점

## 2. 회원 도메인 개발(Done)

    회원 엔티티, 리포지토리, 서비스를 개발해보고 기능 테스트

## 3. 상품 도메인 개발(Done)

    상품 엔티티, 리포지토리, 서비스를 개발해보고 기능 테스트

## 4. 주문 도메인 개발(Done)

    주문 엔티티, 리포지토리, 서비스를 개발해보고 기능 테스트
    그에 더해 주문 관련 검색 기능 구현

## 5. 웹 계층 개발(Done)

    CRUD page, JPA 를 활용하여 Update를 할 때에는 merge 보다는 변경 감지(Dirty-Checking)를 사용하자!
    JPQL과 OrderSearch 객체를 통해 검색 기능 구현.

## 6. 강의가 끝난 후(~ing)

    현재 회사에서 Spring Security 를 통해서 Admin Page 를 만들고 있는데 그것을 활용하여 김영한 개발 팀장님이 말씀하신 로그인/회원가입, 인증-인가 관련된 기능을 스스로 추가해보고자 함
    Ajax를 통한 API 형식의 로그인을 개발할지, Form 형식의 로그인을 개발할지는 미정