## jupyter Notebook

다운로드 방법

* git bash에서 pip install jupyter 엔터

## jupyter Notebook 활용법
블럭형식으로 문서 작성 가능

마크다운 작성 가능

python IDLE 확장 형태로 활용 가능

기본 브라우저를 크롬으로 하는게 가장 좋다.

## jupyter notebook 실행방법

git bash 창에서 jupyter notebook 엔터

만약 크롬탭으로 열리지 않는다면

![1563152926091](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1563152926091.png)

http://localhost 주소로 복 붙

vi ~/.bashrc 엔터 하면 CLI에서 사용할 수 있는 메모장 같은 편집 툴이다.

1. i를 누르면 끼워넣기 모드가 나타난다.

2. alias jn="jupyter notebook" 엔터

3. Esc버튼 누른다.

4. :wq 저장하고 나가기 엔터

   

cat .bashrc 엔터하면 커멘드라인에서 하나 찍어준다?(이해 못함... 질문!)

touch .bash_profile 엔터

* touch  = 새로운 빈 파일을 생성

  

git bash를 새로 킨다면 source .bashrc 후 jn이라고 치면 jupyter notebook을 사용할 수 있다.

! 중요!  작업을 시작할 때 무조건 홈에서 작업한다.

## github에서 8ython clone Downloard ZIP하기

![1563153833091](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1563153833091.png)

여기 파일들을 TIL/python 폴더에 붙여넣는다.

다시 git bash 에서 ls를 쳐보면

![1563153933337](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1563153933337.png)

이렇게 나온다.

이제 jupyter notebook을 실행하면 

![1563153981654](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1563153981654.png)

다음과 같은 형식이 나온다.

바탕에서 h버튼을 누르면 키보드 헬프라인이 나온다.

![1563154058828](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1563154058828.png)

주피터 노트북이 켜져있으면서 git bash에서 끈다면 ![1563154519187](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1563154519187.png)

꺼진다.

## extension Download

다운로드 방법

* git bash에서 pip install jupyter_contrib_nbextensions 엔터

확장 프로그램 설치

* jupyter contrib nbextensions install --user 엔터

구글에 jupyter notebook extension  검색하면 도움말 볼 수 있다.

git bash에 jn 엔터 하면 ![1563154842874](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1563154842874.png)Nbextensions 탭이 생성되어 있다.

table of contents는 활성화 시키자. contents를 새 창으로 확인할 수 있다.