정리

HTML 은 뼈대
CSS 근육(살)
JavaScript (뇌) 

태그는 꺽쇠만 있다만 만들 수 있지만 <abc123>안녕</abc123> 
웹 브라우저는 이해 하지 못 한다. 
그래서 브라우저가 이해하는 언어로 작성을 해주어 한다. 

태그에 모양 
<태그이름>content</태그이름>
<input /> self-closing 태그 

<a><p>원한다면 태그 안에 태그를 사용할 수 있다 </p></a>

<p> <a> 안녕 </p> </a> 태그를 잘못사용하면 제대로 동작이 안될 수 있다. 


속성 
태그는 각각에 맞는 attribute(속성)이 존재 한다. 

<a href="http://naver.com" target="_blank">go to naver.com</a> (작동)
<h1 href="http://naver.com" target="_blank">Hello2!</h1>(작동x)

" " <-- 속성을 사용할 때는 기본적으로 쌍따옴표를 사용해야 한다. 
' '  <-- 물론 사용 가능하지만 권장하지 않음 ! 
` `

IDs 
어떤 태그든 id와 class 를 가질수 있다. 


semantic 
태그에는 의미가 있는 태그가 있고 아무 의미가 없는 태그가 있다. 
semantic : header, main , footer , address 
non-semantic : p, span , div 

가능한  semantic 사용하는 것을 권장 ! 

박스 모델 (css 로 기본값을 변경할 수 있다)
태그에는 기본값으로 block 속성 가진 태그와 inline 속성을 가진 태그가 있다. 


웹 사이트에 설정을 담당하는 태그는  <head> </head> 이다. 


화면(도화지)에 표현 되는 것은 결국 content 이다. !!

























