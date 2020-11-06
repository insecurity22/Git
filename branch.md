##### 1. 새 브런치 만들기

```
명령어
git branch folder/04_example (local에만 만들어짐)

또는 sourcetree의 
ex) 04_Q - 새 브런치로 가지치기
( 현재 04_Q 받아와서 거기서부터 가지치기 )
```
---------------------------------------------------------------------------------------------



##### 2. local과 저장소의 remote branch 생성

```
# VSCode terminal
git push origin folder/04_example
```





##### 2-1. 또는 branch 연동

```
git branch --set-upstream-to folder/04_example 
// 원격 연결로 브런치 gitlab에 올리기
```

=> gitlab 확인

---------------------------------------------------------------------------------------------

##### 4. sourcetree

```
1) 왼쪽 workspace
2) 파일 상태
2-1) 모두 스테이지에 올리기
2-2) commit 작성
2-3) commit 후,
3) push 버튼 누르기

4) 브랜치에 "04_최종" 브랜치 클릭
5) 병합
6) 확인하면 병합
7) push하면 병합 완료
```



추가적으로. 브런치 명령어

```
git branch // 브런치 확인
git checkout 브런치명 // 해당 브런치로 이동, 코드도 바뀜
git branch -d folder/04_example // 브런치 삭제
```

참고 : https://trustyoo86.github.io/git/2017/11/28/git-remote-branch-create.html

---------------------------------------------------------------------------------------------

다른 브런치로 이동할 때

- 파일 상태에 있는 파일들 폐기 하고 이동할 것
- 안그러면 에러 발생 

---------------------------------------------------------------------------------------------

SourceTree remote push 시 "Authentication failed for" 발생 조치법

```
1. 비밀번호 삭제
- Win
   C:\Users\USERNAME\AppData\Local\Atlassian\SourceTree\passwd 삭제.
- Mac
   Keychain Access 실행.
   code.bespinglobal.com 이라는 이름을 가진 로그인 키체인 삭제.
```



출처 :

https://2dubbing.tistory.com/49

https://space.bespinglobal.com/pages/viewpage.action?pageId=24906629
