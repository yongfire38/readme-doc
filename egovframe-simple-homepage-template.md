# 표준프레임워크 템플릿 프로젝트 심플 홈페이지

![java](https://img.shields.io/badge/java-007396?style=for-the-badge&logo=JAVA&logoColor=white)
![javascript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Spring](https://img.shields.io/badge/Spring-F2F4F9?style=for-the-badge&logo=spring)
![jquery](https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

※ 본 프로젝트는 표준프레임워크에서 제공하는 공통컴포넌트의 기능들 중 일부를 선정하여 기본 구성한 참조용 프로젝트 소스입니다.  

## 프로젝트 소개

### 프로젝트 개요

단순 홈페이지 기능 구현 시 필수적인 부분만 사용 가능하도록 경량화 된 실행환경 제공  
메인 페이지, 사용자 관리, 공지사항 관리, 게시판 관리, 안내 관리 기능을 제공

### 메뉴 구성

![menu_sht_v4](https://user-images.githubusercontent.com/30619379/228757232-bf601edb-525a-4db8-b51e-2dd8214fda1c.jpg)

## 참고 화면 및 메뉴 설명

### 메인 화면

![sh1 (1)](https://user-images.githubusercontent.com/30619379/228765034-3b77a060-f770-4c0a-a870-c8600ffa1464.jpg)

1. 홈페이지 템플릿은 관리자만 로그인 가능하다는 전제로 구성되었으며 최초 관리자 계정 설정은 __[ 로그인계정 : admin , 로그인암호 : 1 ]__ 로 설정되어 있다.
2. 관리자 추가 및 변경 기능은 추가 구성되어 있지 않으므로 필요 시 DB를 통해 직접 변경한다. (암호 셋팅 값은 공통컴포넌트의 암호화 로직에 따라 생성해야 함)
3. 기본 기능이나 예시 메뉴를 실무적으로 추가 커스터마이징하여 활용할 수 있다.

### 사이트 소개 화면

![sh2 (1)](https://user-images.githubusercontent.com/30619379/228765143-4ddde792-1ddf-4a53-adfd-b489a654a65c.jpg)

1. 세부메뉴 : 사이트소개, 연혁, 조직소개, 찾아오시는 길
2. 기능설명 : 예시 메뉴에 해당하는 항목으로 샘플 페이지 형태로 링크와 JSP파일이 존재한다.
3. 활용방법 : 각 샘플 페이지에 대한 콘텐츠를 새로 구성하여 활용할 수 있다.

### 정보마당 화면

![sh3 (1)](https://user-images.githubusercontent.com/30619379/228765225-2912ad0e-82ca-4e00-8482-1d6e300c113c.jpg)

1. 세부메뉴 : 주요사업 소개, 대표서비스 소개
2. 기능설명 : 예시 메뉴에 해당하는 항목으로 샘플 페이지 형태로 존재한다.
3. 활용방법 : 각 샘플 페이지에 대한 콘텐츠를 새로 구성하여 활용할 수 있다.

### 고객지원 화면

![sh4 (1)](https://user-images.githubusercontent.com/30619379/228765319-5e2d0ded-4086-43d9-8e3a-a67a3d55b326.jpg)

1. 세부메뉴 : 자료실, 묻고답하기, 서비스신청
2. 기능설명 : 예시 메뉴에 해당하는 항목으로 샘플 페이지 형태로 존재한다.
3. 활용방법 : 각 샘플 페이지에 기능을 추가 개발 후 구성하여 활용할 수 있다.

### 알림마당 화면

![sh5 (1)](https://user-images.githubusercontent.com/30619379/228765560-9f1c3528-8e59-44fd-989d-ece90d2bf95f.jpg)

1. 세부메뉴 : 오늘의행사, 금주의행사, 공지사항, 사이트갤러리
2. 기능설명 : 공통컴포넌트 일정관리(부서일정)와 게시판 기능을 커스터마이징하여 사용한다.
3. 활용방법 : 관리자가 등록한 일정정보를 조회하거나 게시물을 조회할 수 있다.

### 사이트관리 화면

![sh6 (1)](https://user-images.githubusercontent.com/30619379/228765607-108347c5-4b5e-4b8a-8886-b69b144702cd.jpg)

1. 세부메뉴 : 일정관리, 게시판생성관리, 게시판사용관리, 공지사항관리, 사이트갤러리관리
2. 기능설명 : 공통컴포넌트 일정관리(부서일정)과 게시판 기능을 커스터마이징하여 사용한다.
3. 활용방법 : 관리자로 로그인 한 후 일정정보를 등록하거나 게시물을 등록할 수 있다. (게시판 설정 가능)

## 환경 설정

프로젝트에서 사용된 환경 프로그램 정보는 다음과 같다.
| 프로그램 명 | 버전 명 |
| :--------- | :------ |
| java | 1.8 이상 |
| maven | 3.8.4 |

## 프로젝트 실행

1. eclipse 하단의 Servers 탭을 클릭하고, 마우스 우클릭하여 **New > Server** 를 선택하여 서버를 설치한다.

2. 생성 또는 복사된 소스 내부의 DATABASE 폴더 내 dml, ddl을 참고하여 연결하고자 하는 DB에 테이블 생성 및 기초 데이터를 생성한다.  
   dml 및 ddl은 5가지 데이터베이스(Altibase, Cubrid, MySQL, Oracle, Tibero)를 지원한다.

![new_template_sht_run1](https://user-images.githubusercontent.com/30619379/228142767-fa9b4787-ef78-4038-a1b1-749edae9ecb7.jpg)

3. [템플릿 구성 및 환경설정](https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:let4:configration) 문서를 참고하여 템플릿 환경설정을 수행한다.

4. 실행할 프로젝트를 마우스 우클릭하고 **Run As > Run on Server** 를 선택한다.
