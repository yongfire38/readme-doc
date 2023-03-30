# 표준프레임워크 템플릿 프로젝트 내부업무 시스템

![java](https://img.shields.io/badge/java-007396?style=for-the-badge&logo=JAVA&logoColor=white)
![javascript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Spring](https://img.shields.io/badge/Spring-F2F4F9?style=for-the-badge&logo=spring)
![jquery](https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

※ 본 프로젝트는 표준프레임워크에서 제공하는 공통컴포넌트의 기능들 중 일부를 선정하여 기본 구성한 참조용 프로젝트 소스입니다.

## 프로젝트 소개

### 프로젝트 개요

내부업무 기능 구현 시 필수적인 부분만 사용 가능하도록 경량화 된 실행환경 제공  
메인 페이지, 업무사용자 관리, 공지사항 관리, 게시판 관리, 권한 관리, 프로그램 관리, 메뉴 관리 기능을 제공

### 메뉴 구성

![menu_ebt_v4](https://user-images.githubusercontent.com/30619379/228754394-842c2d14-9b2a-426c-adee-b6d86da7c126.jpg)

## 참고 화면 및 메뉴 설명

### 메인 화면

![ebt1](https://user-images.githubusercontent.com/30619379/228750295-b2de6bcc-5b61-434c-adc8-ba61b409aeb4.jpg)

1. 내부업무 템플릿은 업무시스템의 내부적인 관리기능(접속현황 모니터링, 접속제한, 사용자 및 권한 관리 등)을 위주로 기본 구성한 형태이다.  
   최초 로그인 계정 설정은 **[ 로그인계정(관리자) : admin , 로그인암호 : 1 / 로그인계정(사용자) : user1 , 로그인암호 : 1 ]** 로 설정되어 있다.
2. 관리자 계정으로 업무용 사용자(예:user1 계정)을 추가등록하고 권한정보를 부여하는 방식으로 사용할 수 있고 기본 관리기능에 대한 초기 설정을 변경하여 적용할 수 있다.
3. 기본 기능이나 예시 메뉴를 실무적으로 추가 커스터마이징하여 활용할 수 있다.

### 알림정보 화면

![ebt2](https://user-images.githubusercontent.com/30619379/228750762-dd6c1889-dbb5-4a56-ba25-e4135495e4ac.jpg)

1. 세부메뉴 : 공지사항, 업무게시판
2. 기능설명 : 공통컴포넌트 게시판 기능을 커스터마이징하여 사용한다.
3. 활용방법 : 관리자가 등록한 게시물을 조회할 수 있다.

### 직급체계관리 화면

![ebt3](https://user-images.githubusercontent.com/30619379/228750910-f45960ff-be58-46dd-b14c-e248205118c7.jpg)

- **해당 화면 및 세부 메뉴 화면은 구성을 위한 샘플페이지가 제공되며 기능은 구현되지 않은 상태입니다.**

1. 세부메뉴 : 입퇴사정보 관리, 직급정보 관리, 직위정보 관리
2. 기능설명 : 예시 메뉴에 해당하는 항목으로 샘플 페이지 형태로 존재한다.
3. 활용방법 : 각 샘플 페이지에 대한 콘텐츠를 새로 구성하여 활용할 수 있다.

### 진급관리 화면

![ebt4](https://user-images.githubusercontent.com/30619379/228751055-2496a77f-b973-4923-906d-54e5c4a069fa.jpg)

- **해당 화면 및 세부 메뉴 화면은 구성을 위한 샘플페이지가 제공되며 기능은 구현되지 않은 상태입니다.**

1. 세부메뉴 : 업무평가점수 관리, 상벌정보 관리
2. 기능설명 : 예시 메뉴에 해당하는 항목으로 샘플 페이지 형태로 존재한다.
3. 활용방법 : 각 샘플 페이지에 기능을 추가 개발 후 구성하여 활용할 수 있다.

### 근태관리 화면

![ebt5](https://user-images.githubusercontent.com/30619379/228751172-178f3d56-3e5e-46a9-b29b-b212306a2420.jpg)

- **해당 화면 및 세부 메뉴 화면은 구성을 위한 샘플페이지가 제공되며 기능은 구현되지 않은 상태입니다.**

1. 세부메뉴 : 출퇴근정보 관리, 휴무정보 관리
2. 기능설명 : 예시 메뉴에 해당하는 항목으로 샘플 페이지 형태로 존재한다.
3. 활용방법 : 각 샘플 페이지에 기능을 추가 개발 후 구성하여 활용할 수 있다.

### 내부서비스관리 화면

![ebt6](https://user-images.githubusercontent.com/30619379/228751287-05752fef-ea10-4370-8cbc-0f3c472429b3.jpg)

1. 세부메뉴 : 내부업무게시판관리 (게시판생성관리, 게시판사용관리, 공지사항관리, 업무게시판관리), 사용현황관리 (접속로그관리, 접속통계관리, 로그인정책관리)
2. 기능설명 : 공통컴포넌트 게시판 기능, 접속로그, 접속통계, 로그인정책관리를 커스터마이징하여 사용한다.
3. 활용방법 : 관리자로 로그인 한 후 게시물을 등록할 수 있다. (게시판 설정 가능) 접속로그관련 정보를 모니터링 할 수 있다.  
   접속 계정들에 대한 개별 로그인정책을 조회할 수 있다. (접속 제한)

### 내부시스템관리 화면

![ebt7](https://user-images.githubusercontent.com/30619379/228751417-57d136f4-d01e-4def-9f4e-e828c80cb7c0.jpg)

1. 세부메뉴 : 사용자관리 (사용자등록관리, 사용자부재관리), 사용자권한관리 (권한관리, 사용자그룹관리, 사용자별권한관리, 롤관리), 메뉴관리 (프로그램목록관리, 메뉴생성관리, 메뉴목록관리), 코드관리 (분류코드관리, 공통코드관리, 상세코드관리, 우편번호관리)
2. 기능설명 : 공통컴포넌트 사용자관리, 권한관리 (권한, 그룹, 사용자별권한, 롤관리), 메뉴관리 (프로그램, 메뉴, 메뉴생성), 코드관리 (분류코드, 공통코드, 상세코드) 기능을 커스터마이징하여 사용한다.
3. 활용방법 : 관리자로 로그인 한 후 게시물을 등록할 수 있다. (게시판 설정 가능) 사용자와 사용자권한정보를 관리할 수 있다. 프로그램과 메뉴정보를 관리할 수 있다. 내부 코드정보를 관리할 수 있다.

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

![new_template_ebt_run1](https://user-images.githubusercontent.com/30619379/228145073-4580e06f-9ef7-4b04-8f3f-7fee6a0a43af.jpg)

3. [템플릿 구성 및 환경설정](https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:let4:configration) 문서를 참고하여 템플릿 환경설정을 수행한다.

4. 실행할 프로젝트를 마우스 우클릭하고 **Run As > Run on Server** 를 선택한다.
