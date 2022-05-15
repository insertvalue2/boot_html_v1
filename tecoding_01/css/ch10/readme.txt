학습 목표 

flexbox 에 대해 알아 보자. 
(유연한, 2차원 레이아웃에서 잘 작동한다.)


 규칙 1 
flexbox  자식들을 원하는대로 움직이게 하기 위해서는
부모에게만 명시 하면 된다. 
즉 부모 엘리먼트를(태그) flex-container로 만들어 주면 된다. 

규칙 2 (이미지로 확인해주기 !)
주축(main axis) , 교차축 (cross axis)
justify-content , justify (현재 방향 주축을 담당하는 속성 이다.)
align-items (교차 축을 담당하는 속성이다. )    
기본적으로 주축은 수평, 교차축은 수직이다. 
하지만 default 이기 때문에 변경될 수 있다. 
주축 : 가로 , 세로 
교차축 : 세로, 가로

vh = viewport height (스크린에 따라 다름)