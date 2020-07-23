# KJG_board
STS3으로 게시판 만들기

레거시 프로젝트 생성(MVC 패턴 MODEL2방식)

자바버전 1.8 수정
pom.xml 라이브러리 추가(Junit,servlet-api 버전 수정)
(Spring-Test,Spring-JDBC,Hikari커넥션풀,log4jdbc,lombok,mybatis 추가)
OracleDB 테이블 생성(더미 데이터 추가)(select조회)
web.xml UTF-8 encoding ( 한글 설정)
root-context.xml 
db연결 dataSource 작성 
mybatis sqlSessionFactory 작성 및 패키지 등록
log4jdbc.log4j2.properties 작성
jdbc 및 dataSource 테스트코드 작성 후 Junit으로 테스트
VO 클래스생성
mapper 인터페이스 생성
mapper.xml 쿼리문 작성
mapper 테스트코드 작성 후 Junit으로 테스트
service 인터페이스 생성
serviceImpl 생성
service 테스트코드 작성 후 Junit으로 테스트
controller 생성
controller 테스트코드 작성 후 Junit으로 테스트
BootStrap 디자인 참조
각 조회 생성 삭제 수정 jsp 생성
페이징처리 클래스생성(PageDTO)
페이징처리에 따른 controller,mapper인터페이스,xml,service,impl 수정



