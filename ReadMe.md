#Git Test

##Git 을 테스트 하기 위한 프로젝트 입니다.

###git init
~~~
현재 경로를 git이 관리할 수 있게 선언!
~~~
###git config --global user.name "name"
~~~
git 계정 name 등록

git config user.name 을 치면 현재 어떤 name인지 확인 가능
~~~
###git config --global user.email "email"
~~~
git 계정 email 등록

git config user.email 을 치면 현재 어떤 email인지 확인 가능
~~~

###git status
~~~
작업 디렉토리(working directory) 와 스테이징 영역(staging area) 상태를 확인

깃이 관리 하지 않는 파일 or 파일이 수정됨 or 파일이 삭제됨 등등
~~~

###git add
~~~
작업 디렉토리의 변경점을 스테이징 영역에 이동시켜버리기!

git add (filename or directory) : 해당 파일 및 폴더를 스테이징 영역으로!

git add -A : 모든 변경점에 대해 스테이징 영역으로! ( 어떤 경로에서든 동일한 효과 )

git add . :  명령어를 사용한 디렉터리 이하 모두 스테이징 영역으로! 만약 최상위에서 한다면?
             -A와 같은 결과를 보인다.
~~~

