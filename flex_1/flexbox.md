# flexbox



#### step 1) flexbox 선언

*display: flex / inline-flex;*

정렬하고자 하는 요소를 감싸는 부모에게 display를 선언



#### step 2) 가로정렬 / 세로정렬

*flex-direction : row / row-reverse / column / column-reverse ;*

가로 (row) 일 땐 main axis가 가로, cross axis가 세로

세로 (column) 일 땐 main axis가 세로, cross axis가 가로



#### step 3) nowrap / wrap

*flex-wrap : nowrap / wrap ;*

nowrap => 감싸지(wrap) 않고 자식의 사이즈를 줄여서라도 한 줄로 정렬

wrap => 한 줄에 모두 정렬하기에 공간이 넉넉하지 않다면 여러 줄로 정렬



#### step 4) justify-content / align-items, align-content

정렬된 요소들을 *flex-start(시작점으로 정렬) / center(가운데 정렬) / flex-end(끝점에서 정렬) / space-between(요소들 사이 간격을 같게 정렬) / space-around(양옆으로 요소들 사이 간격을 같게 정렬)*

* align-items 는 space-between / space-around 를 사용할 수 없다.
* align-content는 space-between / space-around 사용 가능



<u>Tip!! 선 align-items 후 align-content</u>

