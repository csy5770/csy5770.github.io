#### 작업예정.
- UI 계속진행(VS code) 하면서,
- 자바(스프링-이클립스-egov 전자정부프레임워크 개발환경) 기본실습.
- 오라클DB(SQL디펠로퍼개발환경) 기본실습. Ansi-SQL(표준SQL) 기본언어실습진행 CRUD.
- 2개월 차부터(백엔드), 주로 스프링으로 실습이 진행(납품용-이력서포트폴리오용).
- egov: 자바기반 -> JDK(Java Develoment Kit 자바개발환경) 설치확인.
- JDK 실행 경로 추가.
- java -version (git --version)
- 자바 오라클자바는 8버전부터 비용을 지불해야함. 이 이슈 때문에 오픈JDK로 회사에서 사용.
- 그래서, 오라클자바 8~11버전은 지우고, 오픈 JDK로 변경 후 이클립스 사용할 예정.
- OPEN JDK 8버전(egov와 100% 호환) 사용.
- 톰캣 : 이클립스에서 웹프로그램 결과를 확인하는 라이브 서버(localhost:8080)
- 아파치 : VS code에서 HTML 결과를 확인하는 라이브 서버.(localhost:5500)
- JRE: java Runtime Environment(자바 실행 환경) - 자바앱을 실행할 때
- JDK설치: 개발하고 실행
- 점심후 웹프로젝트1개(헬로월드)-생성play후 지우고,
- 스프링프로젝트1개(헬로자바)-test 폴더에서 자바기초를 실습
- 자바에 익숙해진 후 위 스프링프로젝트를 이용해서 스프링 웹프로젝트를 진행

#### 20210520(목) 작업.
- 메인페이지 시간이 걸리는 부분(백엔드): 최근갤러리, 최근공지사항
- 모바일 게시판페이지(CRUD) CSS 처리 : Read(list, viewpage)
- 카멜표기법(낙타등표기법 예: .bbsListTbl), _표기법(예, .bbs_title)
- href헤르프: hypertext reference (웹문서 참조)
- 정적(static) 콘텐츠: html, css, js
- 동적(dynamic) 콘텐츠: jsp(java 스프링), py(python 장고), PHP, C#
- (데이터변수) 바인딩 : 정적인 컨텐츠에 동적인 데이터를 묶어주는 것을 바인딩이라 함. 
- 오후에 자바(스프링) 개발환경 설치예정.(이클립스:전자정부표준프레임워크설치)
- 전자정부표준프레임워크를 제작한 업체 : 삼성SDS, SK C&C, LG CNS 3개 협업 제작
- 게시물 타이틀 넘치는 부분 CSS 처리
- 모바일 서브페이지 CSS 스타일처리
- 모바일 게시판페이지 CSS 처리
- 태블릿+PC용 CSS 스타일처리
- 모바일+태블릿+PC댓글
- 모바일+태블릿+PC 댓글시스템 CSS+제이쿼리+부트스트랩 처리
- AdminLTE(부트스트랩기반템플릿-반응형)를 이용해서 관리자단 디자인 만들기
- UI디자인 끝 --------------------------------------
- UI 구현 시작 -------------- 스프링프로젝트 시작(자바+ 이클립스+오라클+스프링)
- UI 구현 .......위 에서 제작한 UI디자인 이용해서 프로그램을 입히게 됩니다.

#### 20210518(화) 작업.
- 메인페이지 태블릿 메인 CSS 스타일처리, PC용 메인 CSS 스타일처리
- 반응형 페이지의 핵심기술 미디어쿼리 명령어 사용 + 가로크기를 % (px고정크기가 아닌 비율로 내부 컨텐츠 크기를 지정하는 방법)
- 미디어(PC,스마트폰,프린터,태블릿) + 쿼리(질의어-질문)
- @media 미디어타입(screen, print-all) and (min-width: 801px) {구현내용}
- 태블릿은 마우스 오버 기능을 넣을 필요가 없습니다.(터치스크린)
- 배치1: jQuery 코어 임포트 이후에 사용자가 지정한 js 배치를 해야함.
- 배치2: reset.css, mobile.css 임포트 이후에 사용자가 지정한 tablet.css, pc.css 배치해야 레이아웃이 깨지지 않음.
- 메인페이지 시간이 걸리는 부분(프런트엔드): 메뉴처리, 슬라이딩처리


#### 20210517(월) 작업.
- jQuery 제이쿼리 JSON 데이터 파싱
- 외부data.js 파일에서 Json데이터를 저장한 후 html에서 불러와서 파싱.
- 외부 사이트에서 제공하는(RestAPI서버) json데이터를 html에서 불러와 파싱.
- RestAPI서버 중 코로나19 확진자 데이터를 받아서 html 파싱(데이터를 분해해서 화면에 뿌려주는 작업)
- RestAPI 서버주소(빅데이터): https://coroname.me/getdata
- 수업시작전, jsonData 파싱부분에서 append 사용에 2번 반복되는 부분 확인예정.
- 메인페이지에 자바스크립트(jQuery) 적용.(VS code + HTML5 + CSS + jQuery)
- jQuery 적용 부분: 메뉴, 슬라이드이미지 3개 처리 : 모바일 메인페이지만 마무리
- 보통 이미지 슬라이드 처리는 외부 라이브러리(Lib) 사용(니보슬라이드, 캐로셀슬라이드)
- 외부Lib 사용 않고, 직접 해보기.(완료)

#### 20210514(금) 작업예정
- 구문오류 : syntex 신텍스 오류(문법오류)
- 사용자단 모바일 메인페이지 footer 영역 css 입히기.
- 과제물 제출 준비
- jQuery Json 데이터 파싱 실습
- 8교시에 과제물 다음 카페로 제출
- 메인페이지에 자바스크립트(jQuery)적용. -메뉴, 슬라이드이미지처리, top상단

#### 20210513(목) 작업내역
- 픽사베이 이미지 3개 : 로고1, 슬라이드 이미지1, No image 1, 경로 적어놓기
- 로고: https://pixabay.com/ko/illustrations/%EA%B3%A0%EC%96%91%EC%9D%B4-%EA%B7%B8%EB%A6%BC-%EC%86%90%EC%9C%BC%EB%A1%9C-%EA%B7%B8%EB%A6%B0-2573708/
- 슬라이드 이미지 : https://pixabay.com/ko/photos/%ED%8A%B8%EB%A6%AC-%EA%BD%83-%EC%B4%88%EC%9B%90-%EB%82%98%EB%AC%B4-%EC%A4%84%EA%B8%B0-276014/
- No Image : https://pixabay.com/ko/vectors/%EC%97%91%EC%8A%A4-%EC%B6%9C%EA%B5%AC-%EB%8B%A8%EC%B6%94-%EC%95%84%EC%9D%B4%EC%BD%98-1152114/
- 작업폴더를 나누는 이유: 시청(관공서), 대학, 기업의 웹프로그램(사이트) 제작할 때, 1년간 무상 유지보수 이후 2천, 리뉴얼 4천 비용이 책정(보통)
- home폴더 기존작업물, 리뉴얼 home에 덮어쓰는 방식 아님.
- 리뉴얼 할때 home2022 폴더에 작업을 하시게 됩니다.
- 제이쿼리 코어 다운받기: min버전(압축-속도UP), 일반버전(개발-속도Normal)
- jQuery 미처리 작업은 다음주.
- 오늘부터는 모바일 메인페이지 1개 만들어서 과제물로 제출 -> 스프링에서 프로그램    입히는 소스로 사용하게 됩니다.
- 애니데스크 : 팀뷰어 대신 애니데스크 사용
- html5.html, css.html, js,html 여기까지
- jQuery 기본구조만 실습했습니다.

#### 20210512 (수) 작업내역
- git clone 으로 프로젝트를 가져온 경우 아래 내용을 추가해야 함.
- git config --list 확인에서 user.name, user.email 없으면 아래추가
- 터미널에서 아래 2가지 실행
- git config --local user.name 영문이름
- git config --local user.email 영문이메일
- 프로젝트를 단독 제작하는 경우가 없기에, 2명일 때 소스 수정한 사람 확인용 정보임.
#### 20210511 (화) 작업내역
- 로렘 입숨 한글 http://guny.kr/stuff/klorem/#/table-html
- 로렘 입숨 영어 http://loremipsum.io
- URL 경로(path): /루트, /test/html5.html
- html5의 레이아웃 구조 제작합니다.
- 서버(응답하는프로그램=response) = 아파치서버, 톰캣서버
- 클라이언트(요청하는프로그램=request) = web browser
- HTML은 마크업이 태그로 구성됩니다.<의미있는문자>....</의미있는문자>
- http://127.0.0.1:80[8080|9000|5500|6500]
- PC의 네트워크 내부주소(공통) : 127.0.0.1 == localhost
- 고유주소: yahoo.com == 74.6.231.20(IP주소) == 주민번호(고유)
- IP주소버전: IPv4, IPv6
- HTML 버전: HTML5, HTML4.01(old)
#### 20210510(월) 작업내역
- 업로드절차: 1. 커밋(commit) 2. 푸시(push)
- 다운로드절차: 1. 풀(pull)
- 레포지토리(저장소) 초기화: git init
- 개발PC(html) 와 깃 저장소와 연결시킵니다.
- 포트의 역할이 트렌드로 많이 사용됩니다.
- 포트(port): 포트번호로 서비스를 만드는 것이 트렌드
- 이전에는 80포트에 모든 서비스를 묶어놓았습니다.
- 요즘은 모든 서비스를 개별로 분리하는 트렌드가 있다. : 마이크로 서비스라고 부름 == RestAPI로 구현이 된다.
- 도메인(https://naver.com:1251241/네이버 인증서비스)
- 외부 인원(네이버직원아닌)이 위 포트기준으로 제작한 서비스를 가져다 사용
- html : Hyper Text Markup Language 태그를 사용하는 언어
- md : MarkDown Language 태그를 사용하지 않는 언어
