학습목표 

pseudo selector(가상 클래스 선택자)에 대해 알아 보자. 
좀더 세부적으로 엘리먼트를 선택해 주는 것! (수도우 선택자)


요약 
좀더 세부적으로 엘리먼트를 선택해 주는 것!
(기존 방법 : 태그, id w/#, class w/.)

선택의 복잡한 과정을 pseudo selector로 가능함
ex>
div:first-child {
background-color: tomato;
}

/* pseudo selector */
div:last-child {
background-color: teal;
}

id나 class를 따로 만드는것보다 이렇게 지정하는게 훨씬 좋은 방법이다.
css에서만 선택을 하면 되니까! html코드를 고칠 필요가 없기 때문이다

n번째 태그 수정하기 nth-child(n) 
span:nth-child(2) {
    background-color: teal;
}

span:nth-child(even) { //or odd ( 홀수 )
background-color: teal;
}

even은 짝수! 짝수번째를 모두 바꿀 수있다 오 so cool !


span:nth-child(5n + 1) {
background-color: silver;
}
n을 사용하면 매우 편하다