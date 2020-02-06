
# Git 명령어 정리
    
  + 로컬 저장소에 .git 생성
     + 저장소에 올릴 작업폴더에 가서 git Bash 실행 / 또는 CD [경로] 이동
    
    ```
    $git init
    ```
    
    Initialized empty Git repository in [경로] 

    프로젝트 폴더 안에 .git이라는 숨겨진 폴더가 생성된다.

    내용을 보고 싶다면, 보기에서 숨겨진 파일 보기를 체크


   + git 저장소와 로컬 저장소와 연결
   
    ```
    $git remote add origin "URL"
    ```
    
    ```
    $git remote -v
    ```
    
    + add 
    
    ```
    $git add . | file
    ```

    + 현재 파일들의 상태보기.
    
    ```
    $git status
    ```
    
    + commit
    
    ```
    $commit -m "ㅇㄹㅇㄹㅇ"
    ```
    
    + push
    
    ```
    $git push origin master
    ```

    + pull
    ```
    $git pull
    ```

