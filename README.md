#### 작업예정 : jQuery 제이쿼리 Json 데이터 파싱
- 외부data.js 파일에서 Json데이터를 저장한 후 html에서 불러와서 파싱.
- 외부 사이트에서 제공하는(RestAPI서버) json데이터를 html에서 불러와 파싱.
- RestAPI서버 중 코로나19 확진자 데이터를 받아서 html 파싱(데이터를 분해해서 화면에 뿌려주는 작업)
- RestAPI 서버주소(빅데이터): https://coroname.me/getdata

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
