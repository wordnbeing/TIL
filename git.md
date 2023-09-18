# Git

## 최초설정

커밋에 기록되는 사용자 정보 설정
bash : 터미널에 입력하는 코드
```bash
 git config --global user.name 'moojinkim'
 git config --global user.email 'wordnbeing@gmail.com'
```

## 명령어

- `git init`
    - `.git` : repository를 생성하는 명령어

- `git add <file name>`
    - `working directory`에서 `staging area`로 추가
    - 일반적으로 모든 파일, 폴더를 한번에 추가하기 위해 아래의 명령어로 작성
    - `git add .`

- `git commit -m 'first commit'`
    - `staging arera`에 올라간 파일들의 스냅샷을 찍어 `.git directory`에 자장
    - 일반적으로 -m 옵션을 넣어서 커밋메세지를 추가
    - `git commit -m "message"`

    










