깃 연습 해볼까?
 
커밋 -> 버전이라고 생각 , 체크포인트 



git checkout - --> 최신 커밋




충돌


pull request 

fork - clone - commit -push - pullrequst - review -approve - submit  review -merge pull request 

git rebase pr 충돌 

git rebase and pull request 


amend 

second clone and push 

git commit -a 스테이징 생략 


bad
cherry

good!!!!!!! - want commited

----------------------------------------------

좋은 커밋 메시지 7가지 규칙

제목과 본문을 빈줄으로 분리한다.

제목은 50자 이내로 쓴다

제목을 영어로 쓸 경우 첫 글자는 대문자로 쓴다.

제목에는 마침표를 넣지 않는다.

제목을 영어로 쓸 경우 동사원형(현재형)으로 시작한다.

본무을 72자 단위로 줄 바꿈한다.

어떻게 보다 무엇과 왜를 설명한다. 


-------------------------------------------
Head는 현재 작업중인 브랜치를 가리킵니다.

브랜치는 커밋을 가리키므로 head도 커밋을 가리킵니다.

결국 head는 현재 작업 중인 브랜치의 최근 커밋을 가리킵니다. 

-------------------------------------
git log --oneline --all : 로그 확인 
-------------------------


git revert 를 사용해서 

c1 -< f1 <- c2 <- f2 < -c3 

f 를 제거 할때 
revert
git revert f1 
git revert f2  

-----------------------------------

git reset --har <이동할 커밋>

현재 브랜치를 지정한 커밋으로 옮긴다. 

HEAD~숫자  : 헤드의 부모 커밋, Head~2 는 헤드의 할아버지 커밋  n 번째 조상이라는 의미

Head^ 숫자 부모커밋 HEAD^2 는 병합 커밋 처럼 두번재 부모 

______------------------------

git rest --hard는

git checkout Head~
git branch -f master
git checkout master 

------------------

git tag -a -m <메시지> <tagname>[브랜치 or 체크섬 ]