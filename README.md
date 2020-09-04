# 브랜치 생성과 체크아웃

## 브랜치 생성

### git branch 브랜치명

브랜치를 생성하는 명령어는 git branch이며 첫번째 매개변수는 생성하려는 브랜치명이고 두번째는 분기해 나올 브랜치명이다.

```
$ git branch <branch name>
```

## 브랜치 이동하기(Checkout)

### git checkout (브랜치)

현재 master 브랜치에서 gh-pages 브랜치로 이동하려면 checkout 명령어를 사용한다.

```
$ git checkout <branch>
```

## 커밋하기(commit)

### git commit

git commit -m [설명] 을 작성하면 된다. -m 옵션이 다음에 설명이 온다는 것을 표시한다.

```
$ git commit -m "메시지 내용"
```



