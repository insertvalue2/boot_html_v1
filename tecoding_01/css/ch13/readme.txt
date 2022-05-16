학습목표 

Relative Absolute 에 대해 알아 보자. 


요약 
1. positon: static (default)
2. position: fixed
- element가 처음 생성된 자리에 고정.
3. position: relative;
- element가 '처음 생성된 위치'를 기준점으로, top bottom left right으로 위치를 조금씩 수정할 수 있다.
4. position: absolute;
가장 가까운 relative 부모를 기준으로 이동
position:relative; 를 해주면 부모가 된다.
없으면 body.


많이 사용하는 부분 

absolute 는 부모 위젯에 영향을 받는다 즉 부모 위젯을 relative 만들지 않으면 
body 에 영향을 받는다. !! 