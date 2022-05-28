# reactive-spring-boot-study

[**스프링 부트 실전 활용 마스터**](http://www.yes24.com/Product/Goods/101803558) 책을 읽고 정리하는 공간입니다.

## 작성 가이드
* 매주 Issues 탭에 해당 주차의 범위를 이슈로 발행합니다.
* 해당 이슈 아래에 본인이 정리한 글의 링크를 걸어주시면 됩니다. (공유가능한 플랫폼이면 어떤 플랫폼이든 상관없음)

## 일정
* 1주차(2022/05/31) : [**스프링 부트 웹 애플리케이션 만들기**](https://github.com/hmg0616/reactive-spring-boot-study/issues/1), 발표자 : 

> 종료 후 책거리 및 추후 스터디 진행 도서 선정 예정

## 일정 안지킨 사람
* 1주차(2022/05/31) : 

## 목차
* [1장] 스프링 부트 웹 애플리케이션 만들기
```
스프링 부트란 무엇인가
리액티브 프로그래밍 소개
___리액터 타입
스프링 웹플럭스의 등장
스프링 부트로 이커머스 플랫폼 만들기
___프로젝트 페어런트
___애플리케이션 메타데이터
___스프링 부트 스타터
___스프링 부트 메이븐 플러그인
첫 코드
___자동설정
___컴포넌트 탐색
___스프링 웹플럭스 컨트롤러 생성
템플릿 적용
정리
```

* [2장] 스프링 부트를 활용한 데이터 액세스5
```
리액티브 데이터 스토어 요건
이커머스 애플리케이션 도메인 정의
리포지토리 만들기
테스트 데이터 로딩
장바구니 보여주기
장바구니에 상품 담기
서비스 추출
데이터베이스 쿼리
쿼리문 자동 생성 메소드로 충분하지 않을 때
Example 쿼리
평문형 연산
트레이드 오프
정리
```

* [3장] 스프링 부트 개발자 도구
```
애플리케이션 시작 시간 단축
개발자 도구
___자동 재시작과 리로딩
___정적 자원 제외
___개발 모드에서 캐시 비활성화
___부가적 웹 활동 로깅
___자동설정에서의 로깅 변경
___라이브 리로드 지원
리액터 개발자 도구
___리액터 플로우 디버깅
___리액터 플로우 로깅
___블록하운드를 사용한 블로킹 코드 검출
정리
```

* [4장] 스프링 부트 테스트
```
리액티브 단위 테스트 작성
내장 컨테이너 테스트 실행
스프링 부트 슬라이스 테스트
블록하운드 사용 단위 테스트
정리
```

* [5장] 스프링 부트 운영
```
애플리케이션 배포
___우버 JAR 배포
___도커 배포
운영 애플리케이션 관리
___애플리케이션 정상상태 점검: /actuator/health
___애플리케이션 상세정보: /actuator/info
___다양한 액추에이터 엔드포인트
___로깅 정보 엔드포인트: /actuator/loggers
다양한 운영 데이터 확인
___스레드 정보 확인: /actuator/threaddump
___힙 정보 확인: /actuator/heapdump
___HTTP 호출 트레이싱: /actuator/httptrace
___그 밖의 엔드포인트
관리 서비스 경로 수정
정리
```

* [6장] 스프링 부트 API 서버 구축
```
HTTP 웹 서비스 구축
API 포털 생성
API 진화 반영
하이퍼미디어 기반 웹 서비스 구축
하이퍼미디어의 가치
API에 행동 유도성 추가
정리
```

* [7장] 스프링 부트 메시징
```
메시징 솔루션 선택
익숙한 패턴을 사용한 문제 해결
손쉬운 테스트
테스트컨테이너 사용 테스트
테스트 케이스 구성
스케줄러를 사용해서 블로킹 API 감싸기
컨슈머 작성
정리
```

* [8장] 스프링 부트 R소켓
```
R소켓 소개
리액티브 프로토콜 탄생
R소켓 패러다임
___요청-응답
___요청-스트림
___실행 후 망각
___채널
R소켓 서버 생성
R소켓 클라이언트 생성
___웹플럭스 요청을 R소켓 요청-응답으로 전환
___웹플럭스 요청을 R소켓 요청-스트림으로 전환
___웹플럭스 요청을 R소켓 실행 후 망각으로 전환
___웹플럭스 요청을 R소켓 채널로 전환
정리
```

* [9장] 스프링 부트 애플리케이션 보안
```
스프링 시큐리티 시작하기
실무 적용
스프링 시큐리티 커스텀 정책
사용자 컨텍스트 접근
메소드 수준 보안
OAuth 보안
정리
```

* [한국어판 특별 부록] 리액티브 스트림 시퀀스 다이어그램
```
데이터 핸들러 로직 정의 및 Subscriber 생성
DataProvider에 데이터 요청 및 Publisher 생성
구독하기
Subscription 생성
Subscription에 데이터 요청
실제 데이터 접근 및 onNext/onError/onComplete 호출
비동기는 어디에?
```
