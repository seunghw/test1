github 이용방법

1. git 설치 

2. github 회원가입

3. 우측 상단에 your repositories 눌러서 새로운 repository 생성

4. 생성한 repository url(1) 긁어놓기

5. cmd 창 열기

6. cd 명령어를 통해서 원하는 위치 이동하기 ex) cd C:\project


7. git init 
    새로운 git 저장소가 만들어짐 (숨김 .git 폴더가 생성됨)
8. git clone url(1) 적기

    get clone을 사용하면 repositories와 똑같은 이름의 폴더가 생성되고
    해당 폴더에 소스 코드가 받아짐. 하지만 우리는 빈 repository이므로 폴더만 생성됨

---------------여기까지는 폴더 생성-------------

9. 파일을 작성하고 git add * 을 쳐서 파일을 추가해줍니다
    <git add *> : 전체 파일 add
    <git add 해당파일> : 해당 파일 add

10. git commit -m "작성할 메시지" 작성해줍니다.
    저 ""부분은 추가 메시지를 적는 곳입니다.

11. git push origin (브랜치명) 
    푸시하기




