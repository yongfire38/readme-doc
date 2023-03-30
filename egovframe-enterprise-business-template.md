# 표준프레임워크 템플릿 프로젝트 내부업무 시스템

![java](https://img.shields.io/badge/java-007396?style=for-the-badge&logo=JAVA&logoColor=white)
![javascript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Spring](https://img.shields.io/badge/Spring-F2F4F9?style=for-the-badge&logo=spring)
![jquery](https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

※ 본 프로젝트는 표준프레임워크에서 제공하는 공통컴포넌트의 기능들 중 일부를 선정하여 기본 구성한 참조용 프로젝트 소스입니다.  

## 설명

내부업무 기능 구현 시 필수적인 부분만 사용 가능하도록 경량화 된 실행환경 제공  
메인 페이지, 업무사용자 관리, 공지사항 관리, 게시판 관리, 권한 관리, 프로그램 관리, 메뉴 관리 기능을 제공

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

## 참고 화면 및 메뉴 설명

### 메인 화면

![ebt1](https://user-images.githubusercontent.com/30619379/228750295-b2de6bcc-5b61-434c-adc8-ba61b409aeb4.jpg)

1. 내부업무 템플릿은 업무시스템의 내부적인 관리기능(접속현황 모니터링, 접속제한, 사용자 및 권한 관리 등)을 위주로 기본 구성한 형태이다.  
최초 로그인 계정 설정은 __[ 로그인계정(관리자) : admin , 로그인암호 : 1 / 로그인계정(사용자) : user1 , 로그인암호 : 1 ]__ 로 설정되어 있다.
2. 관리자 계정으로 업무용 사용자(예:user1 계정)을 추가등록하고 권한정보를 부여하는 방식으로 사용할 수 있고 기본 관리기능에 대한 초기 설정을 변경하여 적용할 수 있다.
3. 기본 기능이나 예시 메뉴를 실무적으로 추가 커스터마이징하여 활용할 수 있다.
