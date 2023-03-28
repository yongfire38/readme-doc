# 표준프레임워크 템플릿 프로젝트 심플 홈페이지

※ 본 프로젝트는 표준프레임워크에서 제공하는 공통컴포넌트의 기능들 중 일부를 선정하여 기본 구성한 참조용 프로젝트 소스입니다.  
※ 본 프로젝트는 개발환경에서 eGovFrame > Start > New Template Project 선택 후, Simple Homepage를 체크하여도 동일하게 생성 가능합니다.

## 설명

단순 홈페이지 기능 구현 시 필수적인 부분만 사용 가능하도록 경량화 된 실행환경 제공  
메인 페이지, 사용자 관리, 공지사항 관리, 게시판 관리, 안내 관리 기능을 제공

## 프로젝트 생성

- 개발환경 도구의 템플릿 생성 메뉴를 통해서 템플릿 프로젝트를 생성 및 실행할 경우 1-1. 을 참고한다.
- Git에서 복제하여 설치 시 1-2. 를 참고한다.

### 1-1. 개발환경 도구에서 프로젝트 생성

1. 메뉴 표시줄에서 **File > New > eGovFrame Template Project** 를 선택한다. (단 eGovFrame Perspective 내에서)
   또는, Ctrl+N 단축키를 이용하여 새로 작성 마법사를 실행한 후 **eGovFrame > eGovFrame Template Project** 를 선택하고 Next를 클릭한다.

   ![new_template_wizard1](https://user-images.githubusercontent.com/30619379/228111269-681186ac-66b8-4f24-9e25-7de4c3e9a142.jpg)

2. 생성하려는 Template 유형(단순 홈페이지, 포털 사이트, 내부업무 시스템)을 선택하고 Next를 클릭한다.

   ![new_template_wizard2](https://user-images.githubusercontent.com/30619379/228111295-2d5534e5-9a50-440c-927e-8997ba6b7e8b.jpg)

3. 프로젝트 명과 메이븐 설정에 필요한 값들을 입력하고 Finish를 클릭한다.

   ![new_template_wizard3](https://user-images.githubusercontent.com/30619379/228111310-2ce73886-f2a6-44a4-82dd-eb991886c082.jpg)

### 1-2. Git에서 프로젝트 복제

1. 본 프로젝트 repository 메인 페이지에서 우측 상단의 **[Fork]** 버튼을 클릭하여 나의 Repository에 복사한다.

![new_template_git1](https://user-images.githubusercontent.com/30619379/228111390-574e38e2-c1e4-49d2-9187-9060f9b4ce1c.jpg)

2. 복사된 Repository에서 Contribution을 위한 branch를 생성한다.

3. 표준 프레임워크 개발 환경에서 Git Repositories View에서 Clone a Git Repository를 클릭하여
   Source Git Repository 대화창의 URI 란에 1에서 복사한 나의 원격 저장소의 URL을 붙여 넣으면,
   Host와 Repository path는 자동으로 입력된다.

4. 개발 환경에서 **File > Import... > General > Projects from Folder or Archive** 를 선택하여,
   아래와 같은 대화창에서 복제된 프로젝트를 선택 후 **[Finish]** 버튼을 클릭한다.
5. 자세한 사항은 [표준 프레임워크 소스 복제](https://github.com/yongfire38/egovframe-template-simple-react/wiki/%ED%91%9C%EC%A4%80-%ED%94%84%EB%A0%88%EC%9E%84%EC%9B%8C%ED%81%AC-%EC%86%8C%EC%8A%A4-%EB%B3%B5%EC%A0%9C) 문서를 확인한다.

## 프로젝트 실행

1. eclipse 하단의 Servers 탭을 클릭하고, 마우스 우클릭하여 **New > Server** 를 선택하여 서버를 설치한다.

2. 생성 또는 복사된 소스 내부의 DATABASE 폴더 내 dml, ddl을 참고하여 연결하고자 하는 DB에 테이블 생성 및 기초 데이터를 생성한다.

   ![new_template_sht_run1](https://user-images.githubusercontent.com/30619379/228142767-fa9b4787-ef78-4038-a1b1-749edae9ecb7.jpg)

3. [템플릿 구성 및 환경설정](https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:let4:configration) 문서를 참고하여 템플릿 환경설정을 수행한다.

4. 실행할 프로젝트를 마우스 우클릭하고 **Run As > Run on Server** 를 선택한다.

5. 템플릿 프로젝트의 메뉴 구성 및 기능은 [템플릿 기능](https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:let4:function) 문서를 참조한다.
