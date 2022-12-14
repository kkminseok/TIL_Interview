# TIL_Interview
Today I Learn Interview Study


# 개요

나는 공부를 할 때 원론을 파헤쳐야 한다는걸 알았다.

무작정 외우는건 이해가 안됨 `ex) TCP는 신뢰성이 있다.`

왜 신뢰성 있게 만들어졌는데? 신뢰성이 없어서 문제가 되었던 상황이 뭔데

또 `B-tree는 스케줄러에 쓰입니다.`

스케줄러에 어떻게 쓰이는데, 왜 B-tree가 쓰여야하는데? 

더 이상 Key-Value 형식의 외움은 나한테 도움이 안된다는 것을 알았다. 이해도 안되고 외워지지도 않음.

그렇기에 만들어졌다.

내가 글을 쓰진 않을거다. 나보다 글 잘 쓰는 사람들이 널렸기 때문이다. 내가 고생해서 글 써봤자 나보다 글 잘 쓰는 사람 글 읽는게 훨 이해도 잘된다.

내가 개인적으로 도움을 받았다고 느낀 글들이다.

**모든 것은 주관적으로 판단해야합니다. 나름 거르고 걸렀지만 맞는 정보가 아닐수가 있다는 점.**

-----

## 운영체제 관련

- [운영체제 요약본](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/OS)
- [운영체제 역할](https://cg-developer.tistory.com/385)
- [Blocking, Non-blocking, Sync, Async 댓글도 참조](https://jh-7.tistory.com/25)
- [Green Thread, Native Thread(ex| java)](https://itmore.tistory.com/entry/%EA%B7%B8%EB%A6%B0-%EC%8A%A4%EB%A0%88%EB%93%9C-%EB%9E%80)
- [Green Thread, Native Thread](https://perfectacle.github.io/2019/03/10/green-thread-vs-native-thread/)

## 데이터베이스 관련

- [DB Index와 B-tree의 상관관계, 동작원리](https://brunch.co.kr/@skeks463/25)
- [DB Index가 B-tree를 선택한 이유](https://helloinyong.tistory.com/296)
- [B-tree vs B+tree](https://zorba91.tistory.com/293)
- [샤딩이란](https://d2.naver.com/helloworld/14822)
- [Stored Procedure 기본](https://devkingdom.tistory.com/323)
- [Stored Procedure 장단점(기본)](https://graduation.tistory.com/444)
- [Stored Procedure 성능비교]
- [ORM]
- [ORM과 Stored Procedure 비교]

## 클린코드 관련

- [좋은코드란?](https://jbee.io/etc/what-is-good-code/)
- [단위테스트, 통합테스트](https://cjwoov.tistory.com/9)


```text
SRP, OCP, LSP, ISP, DIP 등은 CleanCode책을 읽는게 제일 이해가 빨랐다.
```

## WEB 개발관련

- [RESTful API란](https://meetup.toast.com/posts/92)
- [Rate limit에 대해서 시리즈별로 읽는걸 추천.](https://etloveguitar.tistory.com/126)
- [gRPC](https://godd.tistory.com/88)
- [gRPC 구조](https://changhoi.github.io/posts/backend/grpc-internals/#gRPC%EC%9D%98-%ED%8A%B9%EC%A7%95)
- [Rest vs gRPC 거의 HTTP/1.x vs HTTP/2.0](https://alledy.netlify.app/posts/rest-vs-grpc/)


```text
# REST API 디자인 가이드
1. url에 'delete'이런 행위를 쓰지마라. 어차피 HTTP Method와 의미가 겹친다/
2. '/'는 계층을 나타내는데 써라.
3. url 너무 길면 하이픈(-)써도된다.
4. (_)는 쓰지마라. 가려질때도 있다.
5. RFC3986(문법 형식)에 따라 경로에는 소문자를 쓰는것을 추천.
6. 파일 확장자 URL에 포함시키지마라. 대신 'Accept header'쓰자.

```

## 네트워크 관련

- [Network 기본](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/Network)
- [3-way-handshake](https://asfirstalways.tistory.com/356)
- [TCP, UDP](https://asfirstalways.tistory.com/327)
- [HTTP/2에 관하여](https://tech.ssut.me/https-is-faster-than-http/)
- [HTTP/3에 관하여](https://ykarma1996.tistory.com/86)
- [HTTP/3에 관하여2 컬럼](https://blog.cloudflare.com/ko-kr/http3-the-past-present-and-future-ko-kr/)
- [CDN](https://www.alibabacloud.com/ko/knowledge/what-is-cdn)

- [요청 흐름](https://github.com/WooVictory/Ready-For-Tech-Interview/blob/master/Network/%EC%A3%BC%EC%86%8C%EC%B0%BD%EC%97%90%20naver.com%EC%9D%84%20%EC%B9%98%EB%A9%B4%20%EC%9D%BC%EC%96%B4%EB%82%98%EB%8A%94%20%EC%9D%BC.md)

> 추가적으로 물리적계층도 지남. 이 포스팅에서는 전송계층까지만 나타냄. <https://ehclub.co.kr/2039> <- 그림 참고>

- [Statueful/Stateless, HTTP, Rest](https://5equal0.tistory.com/entry/StatefulStateless-Stateful-vs-Stateless-%EC%84%9C%EB%B9%84%EC%8A%A4%EC%99%80-HTTP-%EB%B0%8F-REST)
- [Ajax, Fetch, Axios](https://velog.io/@kysung95/%EA%B0%9C%EB%B0%9C%EC%83%81%EC%8B%9D-Ajax%EC%99%80-Axios-%EA%B7%B8%EB%A6%AC%EA%B3%A0-fetch)
- [Promise의 장점](https://poiemaweb.com/es6-promise)




## 언어 관련

### JAVA

- [자바 설치 디렉터리 구조 설명](https://usefultoknow.tistory.com/entry/JDK%EC%99%80-JRE%EB%9E%80-%EC%9E%90%EB%B0%94-API%EB%9E%80)
- [JVM](https://asfirstalways.tistory.com/158)
- [JVM 메모리 상세](https://jwjwj.tistory.com/23)
- [Java GarbageCollection](https://mangkyu.tistory.com/118)
- [Annotation](https://asfirstalways.tistory.com/309)
- [Generic](https://st-lab.tistory.com/153)
- [Java Generic vs C++ Template](https://chchang.tistory.com/entry/C%EC%9D%98-template%EA%B3%BC-Java-generic-method-%EC%99%80%EC%9D%98-%EA%B3%B5%ED%86%B5%EC%A0%90%EA%B3%BC-%EC%B0%A8%EC%9D%B4%EC%A0%90)
- [JAVA Static? final? 정리](https://djkeh.github.io/articles/Why-should-final-member-variables-be-conventionally-static-in-Java-kor/)
- [Override 어노테이션 쓰는 이유](https://team00csduck.tistory.com/11)
- [참조형(CallbyReference)?](https://github.com/WooVictory/Ready-For-Tech-Interview/blob/master/Java/%5BJava%5D%20Call%20by%20Value%20vs%20Call%20by%20Reference.md)
- [String vs StringBuilder vs StringBuffer](https://github.com/WooVictory/Ready-For-Tech-Interview/blob/master/Java/%5BJava%5D%20String%2CStringBuilder%2CStringBuffer%20%EC%B0%A8%EC%9D%B4.md)
- [Wrapper class 쓰는이유](https://github.com/WooVictory/Ready-For-Tech-Interview/blob/master/Java/%5BJava%5D%20Wrapper%20Class.md)
- [== vs equls()](https://github.com/WooVictory/Ready-For-Tech-Interview/blob/master/Java/%5BJava%5D%20%3D%3D%EC%99%80%20equals()%20%EC%B0%A8%EC%9D%B4.md)
- [추상 클래스 vs 인터페이스, 자바가 다중상속을 지원하지 않는 이유](https://brunch.co.kr/@kd4/6)
- [추상 클래스 vs 인터페이스 좀 더 자세한 글](http://alecture.blogspot.com/2011/05/abstract-class-interface.html)
- [Reflection 쉬운버전](https://tecoble.techcourse.co.kr/post/2020-07-16-reflection-api/)
- [Reflection 첫부분 읽을만함](https://gyrfalcon.tistory.com/entry/Java-Reflection)
- [동등성, 동일성](https://pulpul8282.tistory.com/229)
- [컴파일과 빌드](https://itholic.github.io/qa-compile-build-deploy/)

## 기타

- [마샬링(Marshaling)](https://strange-developer.tistory.com/47)
- [직렬화(Serialization)](https://hub1234.tistory.com/26)
- [마샬링 vs 직렬화](https://hyesun03.github.io/2019/09/08/marshalling-vs-serialization/)
- [코루틴](https://wooooooak.github.io/kotlin/2019/08/25/%EC%BD%94%ED%8B%80%EB%A6%B0-%EC%BD%94%EB%A3%A8%ED%8B%B4-%EA%B0%9C%EB%85%90-%EC%9D%B5%ED%9E%88%EA%B8%B0/)
- [병렬성 vs 동시성](https://velog.io/@jaebig/python-%EB%8F%99%EC%8B%9C%EC%84%B1-%EA%B4%80%EB%A6%AC-3-%EC%BD%94%EB%A3%A8%ED%8B%B4Coroutine)
- [불변성 객체](https://seunghyunson.tistory.com/24)
- [Boolean은 왜 1byte일까](https://perfectacle.github.io/2016/12/30/Java-study-001day/)
- [API vs Library](https://eine.tistory.com/entry/%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-API-ABI-%EB%9C%BB-%EB%B9%84%EA%B5%90-%EC%A0%95%EB%A6%AC)
- [배포 전략 카나리, 롤링, 블루/그린](https://onlywis.tistory.com/10)

## 재미, 상식

- [용량에 대하여](https://perfectacle.github.io/2017/01/23/Computer-capacity-fact/)
- [인터넷 속도 상술](https://perfectacle.github.io/2017/01/23/giga-internet-fact/)

## Todo

- Junit사용이유
- 트랜잭션 격리수준