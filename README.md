<h2 align="center">✨ 개발 자료 모음 ✨</h2>  
<p align="center"> 백엔드 개발부터 DevOps까지 자료를 모았습니다.</p>
<p align="center"> 누구나 자유롭게 필요한 자료부터 실질적인 팁까지 함께 공유하고 의견을 나눌 수 있습니다. </p>
<br>

### 커뮤니티 원칙 
<div style="text-align:center">
  
    1. 누구나 자유롭게 질문과 토론을 할 수 있지만, 존중과 예의를 기본으로 합니다.
    2. 자료를 추가할 때는 출처를 명시하고, 저작권을 존중해 주세요.
    3. 기술적 오류나 오래된 정보는 적극적으로 수정 또는 업데이트해 주세요.
    4. 개발 문서 외에도, 개발자로서의 성장과 발전에 도움이 되는 글들도 환영합니다.

</div>
<br>  

### 목차(Table of Contents)  

- [Spring](#spring)
- [MSA](#msa)
- [Database](#database)
- [생각 키우기](#생각-키우기-)
- [안 읽어도 큰일나진 않지만, 추천하고픈 글](#안-읽어도-큰일나진-않지만-추천하고픈-글)

<br>   

### Spring
#### 동영상  
* [Presenting TDD - Mockist - 백명석님](https://www.youtube.com/watch?v=ly-TmUuIXyw)
* [[우아한테크세미나] 200123 우아한모노리스 by 박용권님](https://www.youtube.com/watch?v=SrQeIz3gXZg)

#### 이론
* [JWT의 Refresh Token과 Access Token은 어디에 저장해야 할까? - Heeto님](https://blogeon.tistory.com/m/entry/JWT%EC%9D%98-Refresh-Token%EA%B3%BC-Access-Token%EC%9D%80-%EC%96%B4%EB%94%94%EC%97%90-%EC%A0%80%EC%9E%A5%ED%95%B4%EC%95%BC-%ED%95%A0%EA%B9%8C)
* [Refresh Token과 Sliding Sessions를 활용한 JWT의 보안 전략 - Reid님](https://blog.ull.im/engineering/2019/02/07/jwt-strategy.html)
* [Spring Boot에서 AWS 파라미터 스토어로 private 설정값 사용하기 - 향로님](https://jojoldu.tistory.com/509)
* [상태 기반 테스트 vs 행위 기반 테스트 - 이재용의 iOS님](https://www.wodyd.com/unit-testing-behavior-vs-state/)
* [nGrinder + Springboot 부하 테스트 튜토리얼 - zzangmin code님](https://leezzangmin.tistory.com/42)
* [그라파나(Grafana)란? - 44bits님](https://www.44bits.io/ko/keyword/grafana)
* [프로메테우스와 그라파나로 개발 서버 모니터링하기 - essem님](https://essem-dev.medium.com/%ED%94%84%EB%A1%9C%EB%A9%94%ED%85%8C%EC%9A%B0%EC%8A%A4%EC%99%80-%EA%B7%B8%EB%9D%BC%ED%8C%8C%EB%82%98%EB%A1%9C-%EA%B0%9C%EB%B0%9C-%EC%84%9C%EB%B2%84-%EB%AA%A8%EB%8B%88%ED%84%B0%EB%A7%81%ED%95%98%EA%B8%B0-8942aea724b3)

<br>   

### MSA  
* [MSA 환경에서 장애 전파를 막기 위한 서킷 브레이커 패턴 - Hudi님](https://hudi.blog/circuit-breaker-pattern/)
* [행복을 찾기 위한 우리의 여정 1부, by 쿠팡](https://www.theteams.kr/teams/8226/post/73234)
* [행복을 찾기 위한 우리의 여정 2부, by 쿠팡](https://www.theteams.kr/teams/8226/post/73235)
* [DevOps LGTM 스택 도입기](https://medium.com/finda-tech/lgtm-%EC%8A%A4%ED%83%9D-%EB%8F%84%EC%9E%85%EA%B8%B0-aeb1424b8299)

<br>  

### Database
#### 동영상  
* [DBCP (DB connection pool)의 개념 - 쉬운코드님 ](https://www.youtube.com/watch?v=zowzVqx3MQ4&t=877s)  
* [stored procedure를 백엔드 실무에서 쓰기에 조심스러운 이유 - 쉬운코드님](https://www.youtube.com/watch?v=SOLm-GXFzG8)

#### 이론
* [Exclusive lock과 Shared lock의 차이 - JEONG_AMATEUR 님](https://jeong-pro.tistory.com/94)
* [낙관적 락(Optimistic Lock)과 비관적 락(Pessimistic Lock) - 사바라다님](https://sabarada.tistory.com/175#google_vignette)
* [CAP 이론 소개 - 데이터베이스 초보자용 by N.Damgom님](https://onduway.tistory.com/106)
* [CAP 이론과 PACELC 이론을 알아보자](http://happinessoncode.com/2017/07/29/cap-theorem-and-pacelc-theorem/)
* [MySQL 바이너리 로그(binlog)에 대한 이해 - Jins' Dev Inside님](https://jins-dev.tistory.com/entry/MySQL-%EB%B0%94%EC%9D%B4%EB%84%88%EB%A6%AC-%EB%A1%9C%EA%B7%B8binlog%EC%97%90-%EB%8C%80%ED%95%9C-%EC%9D%B4%ED%95%B4)

<br>  

### 생각 키우기 🌱
공부하거나 개발하면서 궁금했던 점에 대해 `Why?`하는 생각하는 습관 키워요.  

1. Oauth발급시 왜 인가토큰이 먼저나오고 엑세스 토큰을. 또 받아야하는걸까?  
2. 아래와 같이 Java에서 객체 비교를 위해 equals 메소드를 사용하는 경우, 
  
    * tokenType.equals(TokenType.AccessToken)  
    * TokenType.AccessToken.equals(tokenType)
      
    왜 tokenType.equals(TokenType.AccessToken) 대신 TokenType.AccessToken.equals(tokenType)와 같이 메소드 호출 순서를 역으로 수정해야하는 이유는 무엇일까요 ?

3. 왜 Set은 List나 Map으로 자유롭게 변환이 되는걸까?
4. 트랜잭션내에 롤백이 발생할만한 상황을 무엇이 있을까?
5. 데이터의 양이 늘어나면 어떻게 처리할것인가?
6. 대규모 시스템에서는 파티셔닝과 샤딩 중에 어떤 방식이 유리할까요?
7. 파티셔닝은 쿼리 성능은 향상시킬 수 있지만, 테이블 간 조인 비용이 높아질 수 있는데, 어떠한 상황에서 샤딩을 선택하는 것이 좋을까요 ?
8. 대규모 데이터베이스 최적화 측면에서 파티셔닝과 샤딩의 우선순위는 무엇일까요?

<br>    

### 안 읽어도 큰일나진 않지만 추천하고픈 글    
* [스타트업 나쁜 개발 리더 종특 - YJ Min 민윤정님](https://brunch.co.kr/@yj5wqu/27)
