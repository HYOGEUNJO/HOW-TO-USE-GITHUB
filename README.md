# HOW-TO-USE-GITHUB
<깃허브 사용법>

-다운로드-
1. https://github.com/ 
2. https://www.sourcetreeapp.com/
3. https://code.visualstudio.com/
4. https://www.toptal.com/developers/gitignore/     (gitignore.io)

-사용법-
1. 업로드할 파일 생성 (비주얼스튜디오).
2. 리포지토리 폴더 생성 (~~~repo).
3. 리포지토리 폴더에 Git Bash Here 선택.
4. 깃허브의 리포지토리 코드 주소값을 복사 (https://github.com/HYOGEUNJO/HOW-TO-USE-GITHUB.git)
5. 깃배쉬 창(3. 누른이후 나오는 화면)에 "git clone (깃허브주소) ./(파일명)" 입력. (ex. main)
6. 입력후에 리포지토리 폴더(컴퓨터-로컬)를 확인해보면 숨김폴더(.git)폴더와 기존에 깃허브 리포지토리 폴더에 있던 파일들이 복사되어 있음.
7. 불필요한 파일들을 제거하기 위해 .gitignore 파일을 생성.
8. 소스트리를 실행하여 깃배쉬로 생성한 폴더 선택 후 add. (ex. main)
9. 깃배쉬로 생성한 폴더 우클릭하여 Git Bash Here 선택한 다음 
 git config --global user.name "~~~"
 git config --global user.email ~~~@~~~ 과 같이 입력.
10. 깃배쉬 창에서 
 git add
 git commit -m "~~~"
 git push 입력.

* git status 에서 화면이 빠져나가질 않을 경우 q를 누르면 된다.
