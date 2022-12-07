# refactoring-study-14.5th
앱센터 14.5기 웹 리펙터링 스터디 저장소

## 👨‍💻  스터디원

<p>
    <a href="https://github.com/milk717">
      <img src="https://avatars.githubusercontent.com/u/57657868?v=4" width="100">
    </a>
    <a href="https://github.com/YunDH218">
      <img src="https://avatars.githubusercontent.com/u/68414997?v=4" width="100">
    </a>
    <a href="https://github.com/leejiho9898">
      <img src="https://avatars.githubusercontent.com/u/84016039?v=4" width="100">
    </a>
    <a href="https://github.com/leejha">
      <img src="https://avatars.githubusercontent.com/u/57664427?v=4" width="100">
    </a>
    <a href="https://github.com/Martinelli-3535">
      <img src="https://avatars.githubusercontent.com/u/79641160?v=4" width="100">
    </a>
    <a href="https://github.com/Juser0">
      <img src="https://avatars.githubusercontent.com/u/108407945?v=4" width="100">
    </a>
</p>

## 📝 리팩터링 목차
<details>
<summary>목차</summary>
<div markdown="1">

- CHAPTER 01 리팩터링: 첫 번째 예시  
    [1.1 자, 시작해보자!](/ch1/1.1%20자,%20시작해보자!.md)  
    [1.2 예시 프로그램을 본 소감](/ch1/1.2%20예시%20프로그램을%20본%20소감.md)  
    [1.3 리팩터링의 첫 단계](/ch1/1.3%20리팩터링의%20첫%20단계.md)  
	[1.4 statement() 함수 쪼개기](/CHAPTER%2001%20리팩터링%20첫%20번째%20예시/1.4%20statement()%20함수%20쪼개기.md)  
	[1.5 중간 점검: 난무하는 중첩 함수](/CHAPTER%2001%20리팩터링%20첫%20번째%20예시/1.5%20중간%20점검:%20난무하는%20중첩%20함수.md)  
	[1.6 계산 단계와 포맷팅 단계 분리하기](/CHAPTER%2001%20리팩터링%20첫%20번째%20예시/1.6%20계산%20단계와%20포맷팅%20단계%20분리하기.md)  
	[1.7 중간 점검: 두 파일(과 두 단계)로 분리됨](/CHAPTER%2001%20리팩터링%20첫%20번째%20예시/1.7%20중간%20점검:%20두%20파일(과%20두%20단계)로%20분리됨.md)        
	[1.8 다형성을 활용해 계산 코드 재구성하기](/CHAPTER%2001%20리팩터링%20첫%20번째%20예시/1.8%20다형성을%20활용해%20계산%20코드%20재구성하기.md)  
	[1.9 상태 점검: 다형성을 활용하여 데이터 생성하기](/CHAPTER%2001%20리팩터링%20첫%20번째%20예시/1.9%20상태%20점검:%20다형성을%20활용하여%20데이터%20생성하기.md)  
	[1.10 마치며](/CHAPTER%2001%20리팩터링%20첫%20번째%20예시/1.10%20마치며.md)
---
- CHAPTER 02 리팩터링 원칙  
    [2.1 리팩터링 정의](/CHAPTER%2002%20리팩터링%20원칙/2.1%20리팩터링%20정의.md)  
    [2.2 두 개의 모자](/CHAPTER%2002%20리팩터링%20원칙/2.2%20두%20개의%20모자.md)  
    [2.3 리팩터링하는 이유](/CHAPTER%2002%20리팩터링%20원칙/2.3%20리팩터링하는%20이유.md)  
    [2.4 언제 리팩터링해야 할까?](/CHAPTER%2002%20리팩터링%20원칙/2.4%20언제%20리팩터링해야%20할까?.md)  
    [2.5 리팩터링 시 고려할 문제](/CHAPTER%2002%20리팩터링%20원칙/2.5%20리팩터링%20시%20고려할%20문제.md)  
    [2.6 리팩터링, 아키텍처, 애그니(YAGNI)](/CHAPTER%2002%20리팩터링%20원칙/2.6%20리팩터링,%20아키텍처,%20애그니(YAGNI).md)  
    [2.7 리팩터링과 소프트웨어 개발 프로세스](/CHAPTER%2002%20리팩터링%20원칙/2.7%20리팩터링과%20소프트웨어%20개발%20프로세스.md)  
    [2.8 리팩터링과 성능](/CHAPTER%2002%20리팩터링%20원칙/2.8%20리팩터링과%20성능.md)  
    [2.9 리팩터링의 유래](/CHAPTER%2002%20리팩터링%20원칙/2.9%20리팩터링의%20유래.md)  
    [2.10 리팩터링 자동화](/CHAPTER%2002%20리팩터링%20원칙/2.10%20리팩터링%20자동화.md)  
    [2.11 더 알고 싶다면](/CHAPTER%2002%20리팩터링%20원칙/2.11%20더%20알고%20싶다면.md)
---
- CHAPTER 03 코드에서 나는 악취    
    [3.1 기이한 이름](/CHAPTER%2003%20코드에서%20나는%20악취/3.1%20기이한%20이름.md)  
    [3.2 중복 코드](/CHAPTER%2003%20코드에서%20나는%20악취/3.2%20중복%20코드.md) 
    [3.3 긴 함수](/CHAPTER%2003%20코드에서%20나는%20악취/3.3%20긴%20함수.md)  
    [3.4 긴 매개변수 목록](/CHAPTER%2003%20코드에서%20나는%20악취/3.4%20긴%20매개변수%20목록.md) 
    [3.5 전역 데이터](/CHAPTER%2003%20코드에서%20나는%20악취/3.5%20전역%20데이터.md)  
    [3.6 가변 데이터](/CHAPTER%2003%20코드에서%20나는%20악취/3.6%20가변%20데이터.md)  
    [3.7 뒤엉킨 변경](/CHAPTER%2003%20코드에서%20나는%20악취/3.7%20뒤엉킨%20변경.md)  
    [3.8 산탄총 수술](/CHAPTER%2003%20코드에서%20나는%20악취/3.8%20산탄총%20수술.md)  
    [3.9 기능 편애](/CHAPTER%2003%20코드에서%20나는%20악취/3.9%20기능%20편애.md)  
    [3.10 데이터 뭉치](/CHAPTER%2003%20코드에서%20나는%20악취/3.10%20데이터%20뭉치.md)  
    [3.11 기본형 집착](/CHAPTER%2003%20코드에서%20나는%20악취/3.11%20기본형%20집착.md)  
    [3.12 반복되는 switch문](/CHAPTER%2003%20코드에서%20나는%20악취/3.12%20반복되는%20switch문.md)  
    [3.13 반복문](/CHAPTER%2003%20코드에서%20나는%20악취/3.13%20반복문.md)  
    [3.14 성의 없는 요소](/CHAPTER%2003%20코드에서%20나는%20악취/3.14%20성의%20없는%20요소.md)  
    [3.15 추측성 일반화](/CHAPTER%2003%20코드에서%20나는%20악취/3.15%20추측성%20일반화.md)  
    [3.16 임시 필드](/CHAPTER%2003%20코드에서%20나는%20악취/3.16%20임시%20필드.md)  
    [3.17 메시지 체인](/CHAPTER%2003%20코드에서%20나는%20악취/3.17%20메시지%20체인.md)  
    [3.18 중개자](/CHAPTER%2003%20코드에서%20나는%20악취/3.18%20중개자.md)  
    [3.19 내부자 거래](/CHAPTER%2003%20코드에서%20나는%20악취/3.19%20내부자%20거래.md)  
    [3.20 거대한 클래스](/CHAPTER%2003%20코드에서%20나는%20악취/3.20%20거대한%20클래스.md)  
    [3.21 서로 다른 인터페이스의 대안 클래스들](/CHAPTER%2003%20코드에서%20나는%20악취/3.21%20서로%20다른%20인터페이스의%20대안%20클래스들.md)  
    [3.22 데이터 클래스](/CHAPTER%2003%20코드에서%20나는%20악취/3.22%20데이터%20클래스.md)  
    [3.23 상속 포기](/CHAPTER%2003%20코드에서%20나는%20악취/3.23%20상속%20포기.md)  
    [3.24 주석](/CHAPTER%2003%20코드에서%20나는%20악취/3.24%20주석.md)
---
- CHAPTER 04 테스트 구축하기   
    [4.1 자가 테스트 코드의 가치](/CHAPTER%2004%20테스트%20구축하기/4.1%20자가%20테스트%20코드의%20가치.md)  
    [4.2 테스트할 샘플 코드](/CHAPTER%2004%20테스트%20구축하기/4.2%20테스트할%20샘플%20코드.md)  
    [4.3 첫 번째 테스트](/CHAPTER%2004%20테스트%20구축하기/4.3%20첫%20번째%20테스트.md)  
    [4.4 테스트 추가하기](/CHAPTER%2004%20테스트%20구축하기/4.4%20테스트%20추가하기.md)  
    [4.5 픽스처 수정하기](/CHAPTER%2004%20테스트%20구축하기/4.5%20픽스처%20수정하기.md)  
    [4.6 경계 조건 검사하기](/CHAPTER%2004%20테스트%20구축하기/4.6%20경계%20조건%20검사하기.md)  
    [4.7 끝나지 않은 여정](/CHAPTER%2004%20테스트%20구축하기/4.7%20끝나지%20않은%20여정.md)
---
- CHAPTER 05 리팩터링 카탈로그 보는 법  
    [5.1 리팩터링 설명 형식](/CHAPTER%2005%20리팩터링%20카탈로그%20보는%20법/5.1%20리팩터링%20설명%20형식.md)  
    [5.2 리팩터링 기법 선정 기준](/CHAPTER%2005%20리팩터링%20카탈로그%20보는%20법/5.2%20리팩터링%20기법%20선정%20기준.md)
---
- CHAPTER 06 기본적인 리팩터링  
    [6.1 함수 추출하기](/CHAPTER%2006%20기본적인%20리팩터링/6.1%20함수%20추출하기.md)  
    [6.2 함수 인라인하기](/CHAPTER%2006%20기본적인%20리팩터링/6.2%20함수%20인라인하기.md)  
    [6.3 변수 추출하기](/CHAPTER%2006%20기본적인%20리팩터링/6.3%20변수%20추출하기.md)  
    [6.4 변수 인라인하기](/CHAPTER%2006%20기본적인%20리팩터링/6.4%20변수%20인라인하기.md)  
    [6.5 함수 선언 바꾸기](/CHAPTER%2006%20기본적인%20리팩터링/6.5%20함수%20선언%20바꾸기.md)  
    [6.6 변수 캡슐화하기](/CHAPTER%2006%20기본적인%20리팩터링/6.6%20변수%20캡슐화하기.md)  
    [6.7 변수 이름 바꾸기](/CHAPTER%2006%20기본적인%20리팩터링/6.7%20변수%20이름%20바꾸기.md)  
    [6.8 매개변수 객체 만들기](/CHAPTER%2006%20기본적인%20리팩터링/6.8%20매개변수%20객체%20만들기.md)  
    [6.9 여러 함수를 클래스로 묶기](/CHAPTER%2006%20기본적인%20리팩터링/6.9%20여러%20함수를%20클래스로%20묶기.md)  
    [6.10 여러 함수를 변환 함수로 묶기](/CHAPTER%2006%20기본적인%20리팩터링/6.10%20여러%20함수를%20변환%20함수로%20묶기.md)  
    [6.11 단계 쪼개기](/CHAPTER%2006%20기본적인%20리팩터링/6.11%20단계%20쪼개기.md)
---
- CHAPTER 07 캡슐화  
    [7.1 레코드 캡슐화하기](/CHAPTER%2007%20캡슐화/7.1%20레코드%20캡슐화하기.md)  
    [7.2 컬렉션 캡슐화하기](/CHAPTER%2007%20캡슐화/7.2%20컬렉션%20캡슐화하기.md)  
    [7.3 기본형을 객체로 바꾸기](/CHAPTER%2007%20캡슐화/7.3%20기본형을%20객체로%20바꾸기.md)  
    [7.4 임시 변수를 질의 함수로 바꾸기](/CHAPTER%2007%20캡슐화/7.4%20임시%20변수를%20질의%20함수로%20바꾸기.md)  
    [7.5 클래스 추출하기](/CHAPTER%2007%20캡슐화/7.5%20클래스%20추출하기.md)  
    [7.6 클래스 인라인하기](/CHAPTER%2007%20캡슐화/7.6%20클래스%20인라인하기.md)  
    [7.7 위임 숨기기](/CHAPTER%2007%20캡슐화/7.7%20위임%20숨기기.md)  
    [7.8 중개자 제거하기](/CHAPTER%2007%20캡슐화/7.8%20중개자%20제거하기.md)  
    [7.9 알고리즘 교체하기](/CHAPTER%2007%20캡슐화/7.9%20알고리즘%20교체하기.md)
---
- CHAPTER 08 기능 이동  
    [8.1 함수 옮기기](/CHAPTER%2008%20기능%20이동/8.1%20함수%20옮기기.md)  
    [8.2 필드 옮기기](/CHAPTER%2008%20기능%20이동/8.2%20필드%20옮기기.md)  
    [8.3 문장을 함수로 옮기기](/CHAPTER%2008%20기능%20이동/8.3%20문장을%20함수로%20옮기기.md)  
    [8.4 문장을 호출한 곳으로 옮기기](/CHAPTER%2008%20기능%20이동/8.4%20문장을%20호출한%20곳으로%20옮기기.md)  
    [8.5 인라인 코드를 함수 호출로 바꾸기](/CHAPTER%2008%20기능%20이동/8.5%20인라인%20코드를%20함수%20호출로%20바꾸기.md)  
    [8.6 문장 슬라이드하기](/CHAPTER%2008%20기능%20이동/8.6%20문장%20슬라이드하기.md)  
    [8.7 반복문 쪼개기](/CHAPTER%2008%20기능%20이동/8.7%20반복문%20쪼개기.md)  
    [8.8 반복문을 파이프라인으로 바꾸기](/CHAPTER%2008%20기능%20이동/8.8%20반복문을%20파이프라인으로%20바꾸기.md)  
    [8.9 죽은 코드 제거하기](/CHAPTER%2008%20기능%20이동/8.9%20죽은%20코드%20제거하기.md)
---
- CHAPTER 09 데이터 조직화  
    [9.1 변수 쪼개기](/CHAPTER%2009%20데이터%20조직화/9.1%20변수%20쪼개기.md)  
    [9.2 필드 이름 바꾸기](/CHAPTER%2009%20데이터%20조직화/9.2%20필드%20이름%20바꾸기.md)  
    [9.3 파생 변수를 질의 함수로 바꾸기](/CHAPTER%2009%20데이터%20조직화/9.3%20파생%20변수를%20질의%20함수로%20바꾸기.md)  
    [9.4 참조를 값으로 바꾸기](/CHAPTER%2009%20데이터%20조직화/9.4%20참조를%20값으로%20바꾸기.md)  
    [9.5 값을 참조로 바꾸기](/CHAPTER%2009%20데이터%20조직화/9.5%20값을%20참조로%20바꾸기.md)  
    [9.6 매직 리터럴 바꾸기](/CHAPTER%2009%20데이터%20조직화/9.6%20매직%20리터럴%20바꾸기.md)
---
- CHAPTER 10 조건부 로직 간소화  
    [10.1 조건문 분해하기](/CHAPTER%2010%20조건부%20로직%20간소화/10.1%20조건문%20분해하기.md)  
    [10.2 조건식 통합하기](/CHAPTER%2010%20조건부%20로직%20간소화/10.2%20조건식%20통합하기.md)  
    [10.3 중첩 조건문을 보호 구문으로 바꾸기](/CHAPTER%2010%20조건부%20로직%20간소화/10.3%20중첩%20조건문을%20보호%20구문으로%20바꾸기.md)  
    [10.4 조건부 로직을 다형성으로 바꾸기](/CHAPTER%2010%20조건부%20로직%20간소화/10.4%20조건부%20로직을%20다형성으로%20바꾸기.md)  
    [10.5 특이 케이스 추가하기](/CHAPTER%2010%20조건부%20로직%20간소화/10.5%20특이%20케이스%20추가하기.md)  
    [10.6 어서션 추가하기](/CHAPTER%2010%20조건부%20로직%20간소화/10.6%20어서션%20추가하기.md)  
    [10.7 제어 플래그를 탈출문으로 바꾸기](/CHAPTER%2010%20조건부%20로직%20간소화/10.7%20제어%20플래그를%20탈출문으로%20바꾸기.md)
---
- CHAPTER 11 API 리팩터링  
    [11.1 질의 함수와 변경 함수 분리하기](/CHAPTER%2011%20API%20리팩터링/11.1%20질의%20함수와%20변경%20함수%20분리하기.md)  
    [11.2 함수 매개변수화하기](/CHAPTER%2011%20API%20리팩터링/11.2%20함수%20매개변수화하기.md)  
    [11.3 플래그 인수 제거하기](/CHAPTER%2011%20API%20리팩터링/11.3%20플래그%20인수%20제거하기.md)  
    [11.4 객체 통째로 넘기기](/CHAPTER%2011%20API%20리팩터링/11.4%20객체%20통째로%20넘기기.md)  
    [11.5 매개변수를 질의 함수로 바꾸기](/CHAPTER%2011%20API%20리팩터링/11.5%20매개변수를%20질의%20함수로%20바꾸기.md)  
    [11.6 질의 함수를 매개변수로 바꾸기](/CHAPTER%2011%20API%20리팩터링/11.6%20질의%20함수를%20매개변수로%20바꾸기.md)  
    [11.7 세터 제거하기](/CHAPTER%2011%20API%20리팩터링/11.7%20세터%20제거하기.md)  
    [11.8 생성자를 팩터리 함수로](/CHAPTER%2011%20API%20리팩터링/11.8%20생성자를%20팩터리%20함수로.md)  
    [11.9 함수를 명령으로 바꾸기](/CHAPTER%2011%20API%20리팩터링/11.9%20함수를%20명령으로%20바꾸기.md)  
    [11.10 명령을 함수로 바꾸기](/CHAPTER%2011%20API%20리팩터링/11.10%20명령을%20함수로%20바꾸기.md)  
    [11.11 수정된 값 반환하기](/CHAPTER%2011%20API%20리팩터링/11.11%20수정된%20값%20반환하기.md)  
    [11.12 오류 코드를 예외로 바꾸기](/CHAPTER%2011%20API%20리팩터링/11.12%20오류%20코드를%20예외로%20바꾸기.md)  
    [11.13 예외를 사전확인으로 바꾸기](/CHAPTER%2011%20API%20리팩터링/11.13%20예외를%20사전확인으로%20바꾸기.md)
---
- CHAPTER 12 상속 다루기  
    [12.1 메서드 올리기](/CHAPTER%2012%20상속%20다루기/12.1%20메서드%20올리기.md)  
    [12.2 필드 올리기](/CHAPTER%2012%20상속%20다루기/12.2%20필드%20올리기.md)  
    [12.3 생성자 본문 올리기](/CHAPTER%2012%20상속%20다루기/12.3%20생성자%20본문%20올리기.md)  
    [12.4 메서드 내리기](/CHAPTER%2012%20상속%20다루기/12.4%20메서드%20내리기.md)  
    [12.5 필드 내리기](/CHAPTER%2012%20상속%20다루기/12.5%20필드%20내리기.md)  
    [12.6 타입 코드를 서브클래스로 바꾸기](/CHAPTER%2012%20상속%20다루기/12.6%20타입%20코드를%20서브클래스로%20바꾸기.md)  
    [12.7 서브클래스 제거하기](/CHAPTER%2012%20상속%20다루기/12.7%20서브클래스%20제거하기.md)  
    [12.8 슈퍼클래스 추출하기](/CHAPTER%2012%20상속%20다루기/12.8%20슈퍼클래스%20추출하기.md)  
    [12.9 계층 합치기](/CHAPTER%2012%20상속%20다루기/12.9%20계층%20합치기.md)  
    [12.10 서브클래스를 위임으로 바꾸기](/CHAPTER%2012%20상속%20다루기/12.10%20서브클래스를%20위임으로%20바꾸기.md)  
    [12.11 슈퍼클래스를 위임으로 바꾸기](/CHAPTER%2012%20상속%20다루기/12.11%20슈퍼클래스를%20위임으로%20바꾸기.md)
</div>
</details>
 
## 🚨 커밋 메시지 규칙
N주차_이름_목차번호_목차이름   
>**ex) 1주차_김수민_12.11_슈퍼클래스를 위임으로 바꾸기**  

## 🚨 파일 업로드 규칙
자신이 공부한 부분을 마크다운으로 정리해서 해당하는 장의 폴더 안에 업로드한다.
