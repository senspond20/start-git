# git 시작하기

+ ## STEP 01 - github 와 git 준비
    + github 가입 ▶ <https://www.github.com>
    + git 저장소 생성 
    + git download ▶ <https://git-scm.com/downloads>

+ ## STEP 02 - git 최초설정(가입한 gitbub 계정과 연결)
    + 설치가 완료되면 실행 -> Git Bash / 터미널 창을 엽니다.
    
    ```git
    $ git init
    ```
    ```git
    $ git config --global user.name "유저명"
    $ git config --global user.email 이메일주소
    ```
    
    
+ ## 원격저장소의 node_modules 제거하기

### 원격저장소,로컬저장소에서 삭제하기
```
git rm 파일명
git rm -r 폴더명
```
### 원격저장소에서만 삭제하기
```
git rm --cached 파일명
git rm --cached -r 폴더명
```

> 옵션 설명
+ --cached: 원격저장소만 해당
+ -r: recursive(재귀적으로), 디렉토리와 하위 내용 삭제 - 그 외 옵션들

> 사용법
```
git rm --cached -r node_modules
```

