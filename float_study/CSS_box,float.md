## CSS 공부 내용 정리

------

#### [ Box ]

Display속성: box type을 결정짓는 속성

​	Box 종류: Block, Inline, Inline-Block, Flex



##### display: block

box가 한 줄에 하나씩만 들어갈 수 있다.

width를 선언한 경우, 남은 공간을 margin으로 자동으로 채워짐

따로 height를 선언하지 않은 경우, 자식요소의 height의 합 = 부모요소의 height



##### display: inline

텍스트를 작성하듯 오른쪽으로 자연스럽게 흐르는 box type

span tag, anchor 등은 기본 inline 요소이다.

width, height, padding-top, padding-bottom, border-top, border-bottom, margin-top, margin-bottom 사용 불가!



##### display: inline-block

block과 inline의 장점을 모두 가지고 있다.



------

#### [ Float ]

float 속성은 box를 가로로 배치하고자 할 때 사용한다.

float를 적용하면 display속성은 모두 block으로 바뀐다.

float: left/right 가능 => 자신이 갈 수 있는 크기(부모크기)내에서 최대한 왼/오른쪽으로 이동한다.

자식 요소에 float를 적용하면 부모 요소가 해당 자식 요소를 잃게된다.

찾을 수 있는 방법으로는...

1. overflow: hidden; 사용
2. clear 속성 사용

> pseudo-element(가상요소) 만들기
>
> ​	::를 사용하여 적용 => child::before/after{ ... }
>
> ​	속성 내에 **content=" "** 를 필수로 적어준다. (안적어주면 가상요소가 생성이 안됨)
>
> ​	clear속성: float를 무시하게 해준다.
>
> ​	+ display:block; clear:left/right/both;  //clear는 display가 block인 요소만 사용가능하다. 