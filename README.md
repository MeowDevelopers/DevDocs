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
- [데이터베이스](#데이터베이스)
- [생각 키우기](#생각-키우기-)

<br>

### 데이터베이스  
#### 동영상  
* [DBCP (DB connection pool)의 개념 - 쉬운코드 ](https://www.youtube.com/watch?v=zowzVqx3MQ4&t=877s)
* [stored procedure를 백엔드 실무에서 쓰기에 조심스러운 이유 - 쉬운코드](https://www.youtube.com/watch?v=SOLm-GXFzG8)

#### 이론
* [Exclusive lock과 Shared lock의 차이 - 기본기를 쌓는 정아마추어 코딩블로그](https://jeong-pro.tistory.com/94)
* [낙관적 락(Optimistic Lock)과 비관적 락(Pessimistic Lock) - 사바라다는 차곡차곡 블로그](https://sabarada.tistory.com/175#google_vignette)

<br>

### 생각 키우기 🌿
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


