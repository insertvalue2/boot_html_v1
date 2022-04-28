1. 태그 종류 확인 
https://developer.mozilla.org/ko/docs/Web/HTML/Element
https://www.w3schools.com/



https://jupiny.com/2019/03/19/revert-commits-in-remote-repository/
원격 저장소에 올라간 
커밋 취소 후 다시 올리기 

1. 로컬에서 커밋 되돌린 후 강제 푸시

첫번째 방법은 로컬 저장소에서 일단 커밋을 되돌린 후, 이를 원격 저장소에 강제로 반영시키는 방법이다.
1. git reset --hard HEAD~3
2. git push origin master
아래와 같은 에러 문구가 나타날 것이다.
rejected !!! 
2.1 git push -f origin master



2. git revert 사용하기
특정 커밋을 되돌리는 작업도 하나의 커밋으로 간주하여 커밋 히스토리에 추가하는 것이므로, 내가 되돌린 작업을 다른 팀원들과도 공유할 수 있게 된다.
우리가 흔히 사용하는 "실행취소"를 생각하면 이해하기 쉽다.

git push 
