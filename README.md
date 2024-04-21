# 개요
프로 디지털 아카데미 4기 - 프론트엔드 Corworking 실습입니다.

## 프로젝트 목표
저희 프로젝트의 목표는 페어 프로그래밍과 컨벤션을 지켜 실 프로젝트 때 적용할 수 있도록 익숙해지는 것이 목표입니다.
<br />
[페어프로그래밍이란?](https://velog.io/@congaweb/Pair-Programing)


# 참여 인원
<table style="border: 0.5px solid gray">
 <tr>
    <td align="center"><a href="https://github.com/subsub97"><img src="https://avatars.githubusercontent.com/subsub97" width="130px;" alt=""></td>
    <td align="center" style="border-right : 0.5px solid gray"><a href="https://github.com/ShinHeeEul"><img src="https://avatars.githubusercontent.com/ShinHeeEul" width="130px;" alt=""></td>

  </tr>
  <tr>
    <td align="center"><a href="https://github.com/subsub97"><b>김득호</b></td>
    <td align="center"style="border-right : 0.5px solid gray"><a href="https://github.com/ShinHeeEul" ><b>신희을</b></td>
  </tr>

  <tr>
    <td align = "center" colspan = "2" style="border-right : 0.5px solid gray">FE</td>
  </tr>
</table>


# 컨벤션
##  Git 컨벤션
[깃 컨벤션 참조](https://velog.io/@devholic/%EC%9A%B0%ED%85%8C%EC%BD%94-6%EA%B8%B0-%EB%8F%84%EC%A0%84%EA%B8%B0-%EC%BB%A4%EB%B0%8B-%EC%BB%A8%EB%B2%A4%EC%85%98-%EC%84%A4%EC%A0%95-Udacity-%EC%BB%A8%EB%B2%A4%EC%85%98-%EB%B2%88%EC%97%AD-%EB%B0%8F-%EC%A0%95%EB%A6%AC)
```
<컨벤션> : <변경 파일 명> - <설명>
```
 - feat : 새로운 기능과 관련된 것을 의미한다.
 - fix : 오류와 같은 것을 수정했을 때 사용한다.
 - docs : 문서와 관련하여 수정한 부분이 있을 때 사용한다.
 - style : 코드의 변화와 관련없는 포맷이나 세미콜론을 놓친 것과 같은 부분들을 의미한다.
 - refactor : 코드의 리팩토링을 의미한다.
 - test : test를 추가하거나 수정했을 때를 의미한다.
 - chore : build와 관련된 부분, 패키지 매니저 설정 등 여러가지 production code와 무관한 부분 들을 의미한다. 말 그대로 자질구레한 일들이다.

## HTML 컨벤션
- 들여쓰기는 공백(space) 2문자를 사용한다.
- 속성값에는 반드시 큰따옴표("")를 사용한다
- 태그명, 속성명, 속성값 등에는 모두 소문자만 사용한다.
- HTML 문서 형식을 명확하게 지정한다.
- Boolean 속성은 값을 따로 명시하지 않는다.
- 불필요한 태그 작성을 피한다
- 목적에 맞는 HTML 태그를 사용한다.
- 엔티티 참조는 사용하지 않는다.
- css/자바스크립트 파일을 불러오는 경우 type을 명시하지 않는다.
- css는 상단, 자바스크립트는 하단에 불러온다.

## CSS 컨벤션
- 들여쓰기는 공백 2문자를 사용한다
- 클래스, 아이디 명은 -를 사용하는 케밥 케이스를 사용한다.
- 선언 블록은 여는 중괄호({) 앞에 공백 1문자를 넣고 닫는 중괄호(})는 새로운 행에 배치한다.
- 선언시 : 이후 공백 1문자를 추가한다.
- 단일 스타일은 한줄, 다중 스타일은 한줄에 하나씩 표시한다.
- 스타일 지정시 아이디 대신 클래스를 사용한다.
- 자바스크립트 Hook에서 스타일 지정을 위해 만들어진 클래스를 사용하지 않는다.
- 숫자 0값 이후에는 불필요한 단위를 작성하지 않는다.
- border이 없을때는 none이 아닌 0을 사용한다.
- 16진법 컬러는 될 수 있으면 3글자로 표현한다.
- 태그 선택자 대신 클래스 선택자를 사용한다.
- 선택자 길이는 최대 3개이상 넘지 않게 제한한다. 부모선택자를 표시해야한다면 꼭 필요한 경우만 작성한다.
- 축약이 가능한 프라퍼티는 축약해서 사용한다.
- @import 대신 <link>를 사용한다

# 그라운드 룰
- 즐기고 창의적으로 하자
