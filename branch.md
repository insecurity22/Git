1. 새 브런치 만들기

```
git branch folder/04_example (local에만 만들어짐)
```

- 여기서 작업 다하고



2. local과 저장소의 remote branch 생성

```
# VSCode terminal
git push origin folder/04_example
```

- local과 저장소의 remote branch가 생성됨



3. branch 연동

```
git push origin folder/04_example
git branch --set-upstream-to folder/04_example 
// 원격 연결로 브런치 gitlab에 올리기
```



4. sourcetree

```
1) 왼쪽 workspace
2) 파일 상태
2-1) 모두 스테이지에 올리기
2-2) commit 작성
2-3) commit 후,
3) push 버튼 누르기

4) 브랜치에 "04_최종" 브랜치 클릭
5) 병합
6) 확인하면 병합 완료됨
```



추가적으로. 브런치 명령어

```
git branch 				          // 브런치 확인
git checkout 브런치명 			   // 해당 브런치로 이동, 코드도 바뀜
git branch -d folder/04_example	  // 브런치 삭제
```



참고 : https://trustyoo86.github.io/git/2017/11/28/git-remote-branch-create.html