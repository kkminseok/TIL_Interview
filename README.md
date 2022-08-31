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

Reference

- <https://github.com/JaeYeopHan/Interview_Question_for_Beginner>

-----

## 운영체제 관련

- [운영체제 기본](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/OS)
- 

## 데이터베이스 관련

- [DB Index와 B-tree의 상관관계, 동작원리](https://brunch.co.kr/@skeks463/25)

## 클린코드 관련

- [좋은코드란?](https://jbee.io/etc/what-is-good-code/)

> `cleancode`, `DRY`, `OCP`

```text
SRP, OCP, LSP, ISP, DIP 등은 CleanCode책을 읽는게 제일 이해가 빨랐다.
```

## WEB 개발관련

- [RESTful API란](https://meetup.toast.com/posts/92)

> `RESOURCE`, `Verb`, `Representations`, `HTTP Method`

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

> `GET`, `POST`, `UDP`, `TCP`, `HTTP`, `HTTPS`, `DNS round robin`, 

- [3-way-handshake](https://asfirstalways.tistory.com/356)
- [TCP, UDP](https://asfirstalways.tistory.com/327)

> `full-duplex`, `sliding window`, `Nalge Algorithm`

- [HTTP/2에 관하여](https://tech.ssut.me/https-is-faster-than-http/)

> `HTTP vs HTTPS`, `HTTPS/2`, `CDN`

- [요청 흐름](https://github.com/WooVictory/Ready-For-Tech-Interview/blob/master/Network/%EC%A3%BC%EC%86%8C%EC%B0%BD%EC%97%90%20naver.com%EC%9D%84%20%EC%B9%98%EB%A9%B4%20%EC%9D%BC%EC%96%B4%EB%82%98%EB%8A%94%20%EC%9D%BC.md)

> 추가적으로 물리적계층도 지남. 이 포스팅에서는 전송계층까지만 나타냄. <https://ehclub.co.kr/2039> <- 그림 참고>


## 언어 관련

### JAVA

- [JVM](https://asfirstalways.tistory.com/158)
- [Java GarbageCollection](https://mangkyu.tistory.com/118)
- [Annotation](https://asfirstalways.tistory.com/309)
> `Meta Annotation`, `Built-in-Annotation`, `Custom Annotation`

- [Generic](https://st-lab.tistory.com/153)
- [Java Generic vs C++ Template](https://chchang.tistory.com/entry/C%EC%9D%98-template%EA%B3%BC-Java-generic-method-%EC%99%80%EC%9D%98-%EA%B3%B5%ED%86%B5%EC%A0%90%EA%B3%BC-%EC%B0%A8%EC%9D%B4%EC%A0%90)
- [JAVA Static? final? 정리](https://djkeh.github.io/articles/Why-should-final-member-variables-be-conventionally-static-in-Java-kor/)
- [Override 어노테이션 쓰는 이유](https://team00csduck.tistory.com/11)
- [참조형(CallbyReference)?](https://github.com/WooVictory/Ready-For-Tech-Interview/blob/master/Java/%5BJava%5D%20Call%20by%20Value%20vs%20Call%20by%20Reference.md)
- [String vs StringBuilder vs StringBuffer](https://github.com/WooVictory/Ready-For-Tech-Interview/blob/master/Java/%5BJava%5D%20String%2CStringBuilder%2CStringBuffer%20%EC%B0%A8%EC%9D%B4.md)
- [Wrapper class 쓰는이유](https://github.com/WooVictory/Ready-For-Tech-Interview/blob/master/Java/%5BJava%5D%20Wrapper%20Class.md)
- [== vs equls()](https://github.com/WooVictory/Ready-For-Tech-Interview/blob/master/Java/%5BJava%5D%20%3D%3D%EC%99%80%20equals()%20%EC%B0%A8%EC%9D%B4.md)
- [추상 클래스 vs 인터페이스](https://brunch.co.kr/@kd4/6)
- [추상 클래스 vs 인터페이스 좀 더 자세한 글](http://alecture.blogspot.com/2011/05/abstract-class-interface.html)