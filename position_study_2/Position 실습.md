## Position 실습

* **`transform`**

  : **`css transform`** 속성으로 요소에 회전, 크기 조절, 기울이기, 이동 효과를 부여할 수 있다.

   - **`translate()`**

     *transform: translate(x,y)* 

     ​	: 왼쪽에서부터 x거리, 위에서부터 x거리만큼 상대적으로 위치를 정하거나, 이동 및 재배치를 지정

     *transform: translateX()*

     ​	: 좌우(수평 방향)의 이동 거리 값 지정

     *transform: translateY()*

     ​	: 상하(수직 방향)의 이동 거리 값 지정

     *transform: translateZ()*

     ​	: Z방향의 거리 이동을 지정

   - **`rotate()`**

     : 요소를 지정한 각도만큼 회전

   - **`scale()`**

     : x축 또는 y축으로 확대, 축소

   - **`skew()`**

     : 요소를 지정한 만큼 X 또는 Y축으로 기울이기



- img를 부모 요소의 크기에 맞추기

  ```css
  .classname img{
  	display: block;
  	width: 100%;
  	heght: auto;
  }
  ```

  

