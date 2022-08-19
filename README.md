# git-test
git command 테스트를 위한 공간입니다.
<br/>

<hr/>

#### Independant branch 생성
1. 브랜치 생성 <br/>
``` git checkout --orphan [브랜치 이름] ``` <br/>
2. stage 초기화 <br/>
``` git rm --cached -r . ``` <br/>
4. local 초기화 <br/>
``` rm -rf ./* ``` <br/>

<hr/>

#### defalut branch 변경 (예시: master -> main)
1. master 브랜치 이름 변경 <br/> 
``` settings -> branch -> rename branch -> [변경할 브랜치 이름 ( = main)] ``` <br/>
2. 로컬에서 defalut branch 변경 <br/>
``` git config --global init.defaultBranch main ``` <br/>
``` git init ``` <br/>

<hr/>
