# 표준프레임워크 심플 게시판

※ 본 프로젝트는 Spring 기반의 기본 게시판 예제입니다.  
※ 본 프로젝트는 개발환경에서 eGovFrame > Start > New Web Project 선택 후, Generate Example을 체크하여도 동일하게 생성 가능합니다.

## 환경 설정

프로젝트에서 사용된 환경 프로그램 정보는 다음과 같다.
| 프로그램 명 | 버전 명 |
| :--------- | :------ |
| java | 1.8 |
| maven | 3.8.4 |

## 프로젝트 생성

- 개발환경 도구의 템플릿 생성 메뉴를 통해서 템플릿 프로젝트를 생성 및 실행할 경우 1-1. 을 참고한다.
- Git에서 복제하여 설치 시 1-2. 를 참고한다.

### 1-1. 개발환경 도구에서 프로젝트 생성

1. 메뉴 표시줄에서 **File > New > eGovFrame Web Project** 를 선택한다. (단 eGovFrame Perspective 내에서)  
   또는, Ctrl+N 단축키를 이용하여 새로작성 마법사를 실행한 후 **eGovFrame > eGovFrame Web Project** 를 선택하고 Next를 클릭한다.

![4th_new_web](https://user-images.githubusercontent.com/30619379/228182533-6e237576-6eee-4a0d-a682-70a46cbdd44a.jpg)

2. 프로젝트 명과 Maven 설정에 필요한 값들을 입력하고 Next를 클릭한다.

![4th_new_web2](https://user-images.githubusercontent.com/30619379/228182726-53aa819e-ed66-4b15-bf1d-5935300e0c0f.jpg)

3. 예제 소스 파일 생성 여부를 체크하고 Finish를 클릭한다.

![4th_new_web3](https://user-images.githubusercontent.com/30619379/228182782-ffc6947d-0a45-4659-b427-46f2457b1bd4.jpg)

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

2. 실행할 프로젝트를 마우스 우클릭하고 **Run As > Run on Server** 를 선택한다.

3. 자세한 사항은 [프로젝트 설치 및 실행](https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:dev4.1:clntinstall) 문서를 확인한다.
