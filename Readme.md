
git config --global user.name "hde0610"
git config --global user.email "hde0610@naver.com"
맨 처음 깃 설정


mkdir ~/new  :  new라는 이름의 디렉토리 생성
cd ~/new   :  new로 이동
git init  :  깃 저장소 생성
touch Readme.md  :  Readme.md 파일 생성
git status  :  git이 관리 대상 파일들의 상태 파악
git add Readme.md  :  로컬저장소에 파일 추가
git commit -m "Add Resdme.md"  :  추가한 파일에 간단한 설명 달기
git remote add origin https://github.com/hde0610/new.git   :    remote 레퍼지토리 셋팅
git push origin master  :  git에 올리기

vi hello.c

#include<stdio.h>
int main()
{
   printf("Hello World!");
   return 0;
}

git add hello.c  :  hello.c 파일 추가
git commit -m "Add hello.c"   :  파일에 대한 간단한 설명
git remote add origin https://github.com/hde0610/new.git   :   remote레퍼지토리 셋팅
git push origin master  :  git에 올리기

vi hello.c

#include<stdio.h>
int main()
{
   printf("Hello Linux!");
   return 0;
}

git add hello.c   :  변경된 hello.c 파일 추가
git commit -m "Add hello linux"   :   파일에 대한 간단한 설명
git remote add origin https://github.com/hde0610/new.git     :    remote레퍼지토리 셋팅
git push origin master   :   git에 올리기


git 사이트에 확인해보면 hello.c 파일의 내용이 변경되어 있는 것을 확인 할 수 있다.
