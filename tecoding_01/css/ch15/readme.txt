학습 목표 
결합자(combinators)에 대해 알아보자 
https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Selectors
자손 결합자 (div span)
자식 결합자 ( div > span)
인접 형제 결합자 ( ~ )
일반 형제 결합자 ( + )


div의 바로 밑 자식에서 span을 찾아서 그것만 효과를 주는 방법

자손 결합자 

1) 
div span {
text-decoration : underline;
}
이렇게하면 div밑에 있는 모든 span이 효과를 가진다
직접적인 부모가 아니어도 밑에있는 것들을 모두 css가 찾는다.

자식 결합자 
2) div > span {
text-decoration : underline;
}

이렇게하면 바로 밑!!! 을 찾게 되므로 바로 밑의 자식만 건들일수있게된다.

형제에게 효과를 주는방법

p + span {
    color: black;
}
+ 를 사용하면 바로 인접 형제에게 영향을 끼칠 수 있다. 

p ~ span {
    color: black;
}
~ 를 사용하면 일반 형제에게 영향을 끼칠 수 있다. 


 > 를 사용하면 direct child를 찾고, + 를 사용하면 바로 코드상 밑에 있는 sibling을 찾게된다.