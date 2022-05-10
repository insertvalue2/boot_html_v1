학습 목표 
Cascading 의미 

Cascading style sheet 의미? 

브라우저가 CSS 코드를 읽을 때 위에 있는 코드부터 차례차례로 읽는다. 
(extenal css 와 inline css 에서 둘다 같은 대상을 가리키게 된다면 누가 더 영향력이 클까?)
답은 extenal 이든 inline 이든 단지 위에서 부터 차례대로 읽게 된다. 
Cascading 에 의미 이다. 


해설 
CSS 뜻과 작동 방식
CSS : Cascading Style Sheet
Cascading : 위에서 아래로 내려오는 이미지(폭포가 흐르는 것 떠올리기)
어떤 것 다음에 어떤 것이 온다 이것이 cascading이 의미하는 바다.
브라우저가 CSS 코드를 읽을 때 cascading 방식으로, 즉 위에 있는 코드부터 차례차례로 읽힌다.
위에서 아래로 읽는다는 브라우저가 CSS를 읽는 방법을 아는게 가끔 유용하다.
inline CSS와 external CSS 두 CSS 코드가 같은 대상을 가리키게 되면 어떻게 될까?
→ 브라우저는 위에서 아래로 코드를 읽으므로 마지막에 있는 코드가 우리에게 보여지게 된다.
가장 마지막으로 변경된 속성이 우리에게 보여진다.
그래서 코드의 순서를 바꾸면 최종적으로 보여지는 모습이 달라진다.
CSS는 위에서 아래로 작동한다. 결국 적용 되는 건 가장 마지막 코드다.




