# 뚝딱 정형외과 EMR - 병원전산관리시스템
+ 정형외과에서 사용하는 업무 전반을 처리하는 전산 시스템

## 설계 목표
- 기존 EMR의 **데이터 이동 연계성**과 **실시간성** 보완
- **직관적인 화면**과 sweetalert2, 모달 등을 통해 프로그램 조작에 대한 이해를 보다 쉽게 구성
- **부가 기능**을 문자발송API, jspdf, html2canvas, 웹소켓, chart.js, POI 라이브러리 등을 이용해 구현

## 개발 기간
2023.11 ~ 2024.01
[개발기간]

## 주요 기능
- 공통 : 공지사항, 실시간 채팅, 일정 확인, 환자 관
- 원무과 : 진료 예약 및 접수, 입퇴원, 수납, 발주 결재, 문자 발송
- 의사 : 진료 차트, 회진 차트, 일정 관리, 의료 통계
- 간호사 : 오더 수행(의사 진료 후 검사/처치), 병동 관리, 약품 관리, 근무 확인 및 조정
- 치료사 : 치료실 배정, 치료일지/통계
- 인사과 : 사원 관리, 진료실 배졍, 인사 통계

## 사용기술 및 개발환경
|Category | Detail |
| ------- | ------ |
| FrontEnd | HTML5, XML, CSS3, JavaScript, Ajax, JSON |
| BackEnd  | Java(JDK 1.8), JSP |
| FrameWork| Spring(4.3.2), Maven(4.0.0) |
| OS       | Windows 10, 11 |
| IDE      | Eclipse, tortoise SVN, redmine, Erd Cloud |
| Server   | Apatch Tomcat(v8.5) |
| DataBase | Oracle(11g) - SQL Developer(17.4.1.054) |
| ORM | MyBatis |

## 사용API 및 기술 : 사용/구현 부분
- 공공 데이터 의약품 API : 약품 코드 사용
- 공공 데이터 상병코드 API : 질병 코드 사용
- js PDF : PDF 파일 출력
- coolsms : 문자 발송
- Chart.js : 통계
- High Chart : 지도 통계
- CKEditor : 게시판
- SweetAlert : alert창 대체
- WebSocket : 실시간 채팅
- Apache Poi : Excel 업로드, 다운로드
- jsTree : 오더세트(트리구조)

## ERD
[ERD]
-----

## 참고
Dr.palette <https://dr.pltt.cloud/intro>
