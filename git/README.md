# 멀티미디어 실습

> 2023-2학기 GIT 실습 수업 정리

## 2023-10-04
### Staging area(스테이징 영역)
- IT 프로젝트는 여러 파일을 동시에 다루게 된다.
- 일반 문서 수정과 같이 `저장` 버튼만으로 한번에 수정한 파일들을 저장하게 하면, 불필요한 파일들이 commit에 포함되는 일들이 발생한다.
  - 예시 :
    - `.vs` : vs로 프로젝트를 열었을 때 자동 생성되는 폴더
- 그래서 Staging area라는 영역을 따로 두고, commit에 포함될 code(file)만 스테이징 영역에 추가하게 한 다음, commit을 만든다.
  - 스테이징 영역에 파일을 추가할 때 쓰는 명령어: `git add filename`

## 2023-09-27
- commit 이란?
  - GIT에 기본 단위로 논리적 변경이 있을 때 만든다. (사진찍기와 유사)
  
- commit Message
  - 코드 변경본을 한마디로 축약하여 설명한 것.

- 명령어

  - ```git commit -m "commit Message를 이곳에 입력"```
  - ```git commit -message "commit Message를 이곳에 입력"```  

- 얼마나 자주 commit을 만들어야 하나?
  - 너무 작지도, 크지도 않게 한다.
  - commit 단위가 너무 작을 경우 불필요한 commit이 생성됨
  - commit 단위가 너무 클 경우 장애시 빠른 대응이 힘듬
  - 예시 : 30분 안에 리뷰 가능하도록 commit


  