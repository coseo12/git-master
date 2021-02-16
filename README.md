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
  - Mac🍎:
    ```
    $ git config core.autocrlf input
    ```
  - Windows🖥:
    ```
    $ git config core.autocrlf true
    ```

## 초기화

```
$ git init
```

## Git ignore

예외처리 설정 파일

```
$ touch .gitignore
```

## Log 포멧 설정

```
$ git log --graph --all --pretty=format:'%C(yellow)[%ad]%C(reset) %C(green)[%h]%C(reset) | %C(white)%s %C(bold red){{%an}}%C(reset) %C(blue)%d%C(reset)' --date=short
```

alias 설정

```
 git config --global alias.hist "log --graph --all --pretty=format:'%C(yellow)[%ad]%C(reset) %C(green)[%h]%C(reset) | %C(white)%s %C(bold red){{%an}}%C(reset) %C(blue)%d%C(reset)' --date=short"
```
