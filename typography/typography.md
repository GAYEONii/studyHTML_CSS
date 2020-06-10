# Typography

: 텍스트를 예쁘게 디자인하기



### font-size

**: 글씨 크기 설정**

<span style="color:blue">단위: px, em, rem</span>

em => equal to capitalM (실제로 적용된 폰트 사이즈 기준)

rem => rootEm (html에 적용된 폰트 사이즈 기준)



### line-height

**: 줄 간격**



### font-weight

**: 글자 굵기**

<span style="color:orange">400 regular</span>

<span style="color:orange">**700 bold**</span>



### font-family

**: 폰트 서체**

폰트가 없는 경우를 대비하여 여러개 작성 가능

<span style="color:gray">*serif: 명조체 느낌나는 서체*</span>

<span style="color:gray">*sans-serif: 돋움, 고딕 느낌나는 서체*</span>



### color

**: 글자 색상**

<span style="color:orange">hex, rgb, rgba(alpha: 투명도 설정)</span> 로 설정가능



### text-align

**: 글자 정렬**

left, center, right



### text-indent

**: 들여쓰기**

px로 사이즈 조절 ( -px는 내어쓰기 )



### text-transform

**: (영어에 적용 가능한 속성) 글자 변형**

none => 변화 없음

capitalize => 첫 글자만 대문자

uppercase => 모두 대문자

lowercase => 모두 소문자



### text-decoration

**: 텍스트 줄 O, X**

none,  <u>underline</u>, ~~line-through~~, overline(글자 위 밑줄)



### font-style

: 텍스트 기울이기

nomar, *italic, oblique*

cf) html 요소로 <em>이라는 강조 태그가 존재하는데, 기본 스타일이 italic이다. 이 때 normal속성으로 바꾸고자 할 때 font-style을 주로 사용한다.



## [ Web font ]

- 가져다 쓰기

<span style="color:blue">=> fonts.google.com 에서 복붙해서 사용하기</span>

- 직접 제공하기

@font-face{

​	font-family:

​	font-style:

​	font-weight:

​	src: url()

}



==> **font 불러오기**

- html에 <link rel = "stylesheet" href="./style.css">
- css에 @import url("_____") 하고 font-family 적용