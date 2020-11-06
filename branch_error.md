1. branch 강제 삭제

```
$ git checkout master
$ git branch -d Test_Branch

아래의 에러가 뜬다면
error: The branch 'feature/ ... ' is not fully merged.
If you are sure you want to delete it, run 'git branch -D ...

$ git branch -D Test_Branch
```

https://stackoverflow.com/questions/41492254/deleting-a-local-branch-with-git



2. Push 오류

error: failed to push some refs to 관련 오류

- 원격에 있는 소스가 로컬에 반영이 안되서
- 처음에 branch 따고, 로컬이랑 원격이랑 연결시키는 명령어 써줘야함

https://okky.kr/article/381838
