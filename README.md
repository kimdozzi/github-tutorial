## how to use github ?!

<br>

### git 초기설정
    git config --global user.name "dohyung kim"
    git config --global user.email "neo5188@gmail.com"
    git config --list
=> user.name 과 user.email 확인하기 ! 

<br>


### name, email, branch 확인하기 
    cat ~/.gitconfig

<br>


### default 브랜치 변경
    git config --global init.defaultBranch main

<br>


### 브랜치 변경
    git checkout -B main
    git push -u origin main

<br>


### git 저장소 식별 및 파일 올리기
    git clone url # 식별 
    git add . or git add filename
    git co	mmit -m " message "  
    git status
    git push 

<br>


### git repo에 소스코드 올리기
    1. 소스코드를 vscode에 옮기기
    2. terminal -> new terminal
    git pull
    3. git add .
    4. git status (필수아님)
    5. git commit -m " message "  
    6. git remote add origin url
    7. git push origin main or git push
