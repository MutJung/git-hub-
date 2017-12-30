Git hub 사용법
=================================
git hub를 사용해보자
-------------------------------
1. git hub 계정 생성
2. git download
3. git-hub repository 만들기
    * 그러면 저장소 주소가 생긴다 ex)https://github.com/MutJung/test.git
    * MutJung 은 아이디, test 는 repository 이름이다.

4. 원하는 디렉터리를 git-hub repository 에 연결시키기.
    1) git bash 또는 윈도우 cmd 창을 이용해 github repository 와 연결을 원하는 디렉터리로 이동
    2) **git init**
    3)  
       **git add .**        -->>전체 다 관리대상에 추가

       **git add OOO.txt** -->> OOO.txt 파일을 관리대상에 추가
    4) **git commit -m "[COMMIT_NAME]"**
        * ex) git commit -m "first commit"
        * add 시킨 것들을 commit 한다
        * 관리 대상에 있는 것들을 다 커밋한다 커밋네임을 정해서
    5) **git remote add origin [GITHUB_REOISITORY_주소]**
        * ex) git remote add origin https://github.com/MutJung/test.git
        * github repository 주소의 별명을 origin 으로 하겠다 귀찮으니까
    6) **git push -u origin master**
        * origin 주소에 master 가지를 만들어서 push 합니다.
        * 이렇게 해놓으면 나중에 **git push** 만 해도 된다.
zz
