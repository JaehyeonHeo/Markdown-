# 📚마크다운 문법 학습📚

>마크다운(markdown)은 일반 텍스트 기반의 경량 마크업 언어이다. 일반 텍스트로 서식이 있는 문서를 작성하는 데 사용되며, 일반 마크업 언어에 비해 문법이 쉽고 간단한 것이 특징이다. HTML과 리치 텍스트(RTF) 등 서식 문서로 쉽게 변환되기 때문에 응용 소프트웨어와 함께 배포되는 README 파일이나 온라인 게시물 등에 많이 사용된다. 
>>위키백과

____

## 🔸 마크다운의 특징

```
- 확장자
  README.md 
  
- 장점 
  1.문법이 쉽다.
  2.관리가 쉽다.
  3.지원 가능한 플랫폼과 프로그램이 다양하다.
  
- 단점 
  1.표준이 없어 사용자마다 문법이 상이할 수 있다.
  2.모든 HTML 마크업을 대신하지 못한다.
```
____
## 🔸 문법

## 1. Headers(제목)

* 주제목 
>아래와 같이 작성하면 결과값이 그 아래와 같이 표현됨
```
This is an H1
=============
```
  This is an H1
  =============

* 부제목  

```
This is an H2
-------------
```
  This is an H2
  -------------

* 제목 글자 크기 : 1~6까지만 지원
>아래와 같이 작성하면 결과값이 그 아래와 같이 표현됨
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
____
## 2.  인용문
이메일에서 사용하는 > 블럭인용문자를 이용한다.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.
____
## 3. 목록
* 순서있는 목록
순서있는 목록은 숫자와 점을 사용한다.
```
1. 첫번째
2. 두번째
3. 세번째
```
1. 첫번째
2. 두번째
3. 세번째

* 순서없는 목록(글머리 기호: *, +, - )
```
* 주제목
  * 부제목
    * 세부제목

+ 주제목
  + 부제목
    + 세부제목

- 주제목
  - 부제목
    - 세부제목
```
* 주제목
  * 부제목
    * 세부제목

+ 주제목
  + 부제목
    + 세부제목

- 주제목
  - 부제목
    - 세부제목
____
## 4. 코드블럭
백틱(`) 또는 ~ 세 개를 사용하여 코드 블럭을 작성할 수 있다.

> 위 아래 3개로 감싸면 블럭으로 만들 수 있다.

> 블럭으로 작성하면 여러 줄을 작성할 수 있다.

```
위 아래 3개로 감싸면 블럭으로 만들 수 있다.

블럭으로 작성하면 여러 줄을 작성할 수 있다.
```
____
## 5. 코드 하이라이트 
백틱 3개 뒤에 언어 이름을 넣으면 코드 하이라이트 가능

```javascript
let sumNumbers = (firstNum, lastNum) => {
  return firstNum + lastNum;
};
sumNumbers(100, 200);
```
____
## 6. 링크(Link)
>인라인 링크와 Url 링크, 참조 링크로 표현할 수 있다.
```
[GOOGLE](https://google.com)

 
[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")

 
[상대적 참조](../users/login)
```
[GOOGLE](https://google.com "구글로 이동합니다.")

 
[NAVER](https://naver.com "네이버로 이동합니다.")

 
____
## 7. 수평선(Horizontal Line)
*, -, _ 등을 3개 이상 사용하여 작성할 수 있다.

띄어쓰기를 중간에 삽입하여도 가능하다.

다만, 하이픈-은 헤더로 인식할 수도 있으니 주의해서 사용할 필요가 있다.
____
## 8. 이미지(Image)
이미지를 표현할 수 있다.
```
![이미지 설명](이미지 링크 "이미지에 대한 설명 링크")
```
![바탕화면 캡쳐](https://raw.githubusercontent.com/JaehyeonHeo/Markdown-/0b23951c9bd7d4e9c25e61feabb05423d76551e0/images/%EC%9D%B4%EB%AF%B8%EC%A7%80%20001.jpg "이미지에 대한 설명 링크 걸기")
____
## 9. 체크박스(Check Box)
> -, *, + 뒤에 띄어쓰기 후 (대괄호)를 넣어 작성할 수 있다. 대괄호안에 띄어쓰기를 하면 빈 체크박스, X(대문자)를 넣으면 체크된 체크박스가 생긴다.
```
- [ ] 우유 사오기
- [x] 택배 찾기 
```
> 결과 

- [ ] 우유 사오기

- [x] 택배 찾기 
____
## 10. 이모지 

😆🙏❤☀ 다양한 이모지를 사용가능하다.
* 첫번째 방법 : 단축키 
  Window : 윈도우 키 + 마침표(.)
  
* 두번째 방법 : 사이트 활용

  🛡 [트위터 기호 사이트](https://kr.piliapp.com/twitter-symbols/ "트위터 기호 사이트로 연결")

  ![트위터 이모지 활용 사이트](https://raw.githubusercontent.com/JaehyeonHeo/Markdown-/0b23951c9bd7d4e9c25e61feabb05423d76551e0/images/%EC%9D%B4%EB%AF%B8%EC%A7%80%20003.jpg "트위터기호")  

____

## [🔙뒤로](https://github.com/JaehyeonHeo?tab=repositories "레파지토리 목록")


