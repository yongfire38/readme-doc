# 표준프레임워크 부트 기반 심플 게시판

※ 본 프로젝트는 Spring boot 기반의 기본 게시판 예제입니다.  
※ 본 프로젝트는 개발환경에서 eGovFrame > Start > New Boot Web Project 선택 후, Generate Example을 체크하여도 동일하게 생성 가능합니다.

## 프로젝트 생성

- 개발환경 도구의 템플릿 생성 메뉴를 통해서 템플릿 프로젝트를 생성 및 실행할 경우 1-1. 을 참고한다.
- Git에서 복제하여 설치 시 1-2. 를 참고한다.

### 1-1. 개발환경 도구에서 프로젝트 생성

1. 메뉴 표시줄에서 **File > New > eGovFrame Boot Web Project** 를 선택한다. (단 eGovFrame Perspective 내에서)  
   또는, Ctrl+N 단축키를 이용하여 새로작성 마법사를 실행한 후 **eGovFrame > eGovFrame Boot Web Project** 를 선택하고 Next를 클릭한다.
   
![4th_new_boot_web1](https://user-images.githubusercontent.com/30619379/228182182-0039fd92-00f4-4bfc-b43f-f8b39e6b75f1.jpg)

2. 프로젝트 명과 Maven 설정에 필요한 값들을 입력하고 Next를 클릭한다.

![4th_new_boot_web2](https://user-images.githubusercontent.com/30619379/228182258-e0d3f59a-d524-4a97-b639-75578cd5ff97.jpg)

3. 예제 소스 파일 생성 여부를 체크하고 Finish를 클릭한다.

![4th_new_boot_web3](https://user-images.githubusercontent.com/30619379/228182289-b650d84b-e298-48f1-a47f-b3da1daa970d.jpg)

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

### CLI 구동 방법

```bash
mvn spring-boot:run
```

### IDE 구동 방법

개발환경에서 프로젝트 우클릭 > Run As > Spring Boot App을 통해 구동한다.

## 변경 사항

### 1. [Java Config 변환](./Docs/java-config-convert.md)

#### 1) Web.xml -> WebApplicationInitializer 구현체로 변환

#### 2) context-\*.xml -> @Configuration 변환

#### 3) properties 변환(예정) boot 지원
