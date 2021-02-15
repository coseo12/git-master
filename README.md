# Git Master Class

    Git 마스터 과정

## 필요 프로그램

- [Mac용 추천 터미널](https://www.iterm2.com/)
- [Windows용 추천 터미널](https://cmder.net/)
- [iTerm setting](https://gist.github.com/kevin-smets/8568070)

## SETUP

- Editting 설정
  git config --global core.editor "code --wait"
  git config --global -e

- 사용자 설정
  ```
  $ git config --global user.name "username"
  $ git config --global user.email "user@email.com"
  ```
- 줄바꿈 설정
  - MAC:
    ```
    $ git config core.autocrlf input
    ```
  - Windows:
    ```
    $ git config core.autocrlf true
    ```

## 초기화

```
$ git init
```

## 상태

```
$ git status
```

## Git Workflow

- Working directory: work area

- stating area: add

- .git directory: commit

## Git stating

- 추가

  ```
  $ git add [file_name]
  ```

- 제거

  ```
  $ git rm --cached [file_name]
  ```

## Git ignore

예외처리 설정 파일

```
$ touch .gitignore
```

## Git commit

- commit
  ```
  $ git commit -m "message"
  ```

## git diff

수정 정보 확인

```
$ git diff
```
