KH정보교육원 Semi Project : WineFine project

참여자 : 김유진, 김한솔(팀장), 박경화, 연경흠, 지수빈, 최한일

1. 개요
와인 입문자들을 위한 와인 상품의 정보와 구매처를 마련하고, 이용자의 성향을 파악하여 맞춤 와인을 추천할 수 있는 서비스를 제공

2. 구현 기능
가. 사용자
- 마이페이지(나의 정보 수정, 나의 주문 내역, 장바구니, 나의 문의 내역, 나의 리뷰 내역)
- 사이트 회원 서비스(회원가입, 로그인, 아이디/비밀번호찾기)
- 와인카테고리(전체조회, 종류별·맛별·산지별·가격대별 조회)
- 내게 맞는 와인찾기
- 상품 상세페이지(상품상세정보, 교환 및 반품안내, 상품후기, 상품문의)
- 와인스토어(구매하기, 장바구니, 결제, 픽업시스템
- 게시판(용어사전, 와인매거진, 와인 페어링)
- 고객센터(공지사항, 이벤트, 1대1문의, Contact Us, FAQ)

나. 관리자
- 사이트 회원관리(전체 회원정보조회, 개별 회원정보조회, 회원탈퇴관리, 블랙리스트 회원 관리)
- 주문정보관리(전체 주문 내역 확인, 개별 주문 정보 확인)
- 재고관리(재고 관리 페이지 관리)
- 통계(재고 통계, 수익 통계, 주문내역통계)
- 내게 맞는 와인 찾기 페이지 관리
- 와인 카테고리관리(전체조회, 베스트셀러, 종류별·맛별·산지별·가격대별 조회)
- 상품상세페이지 관리(상품상세정보 관리, 상품후기(리뷰) 관리, 상품문의 관리)
- 게시판 관리(용어사전관리, 와인매거진관리, 와인페어링)
- 고객센터 관리(공지사항 관리, 이벤트 게시판 관리, 1대1문의 관리, Contact Us, FAQ 관리)

3. 설계의 주안점
와인은 대중화 되어 있으나 와인이 어려운 사람들(와인에 입문하고자 하는 사람들)을 위해서 자신의 취향에 맞는 와인을 찾을 수 있게 해주는 소울 와인 찾기 기능, 와인에 대해 쉽게 설명해주는 와인 용어 사전 등이 존재한다.
다양한 와인의 정보를 데이터 베이스에 저장하고, 이에 세부적인 카테고리를 통해 접근해 읽어오도록 설계하고자 하였다.

4. 사용기술 및 개발 환경
- Language : Java 8, CSS3, HTML5, JavaScript 
- DB: Oracle 11g EE 
- Library : JDBC – ojdbc6, jQuery 3.6.0, UI – bootstrap4,
- Tool :Eclipse IDE (2020-03), Kakao Oven, ,Oracle SQL Developer(21.4.3), Visual Studio Code(1.66.2), ERDCloud 
- WAS: Apache Tomcat (8.5.78)
- 협업프로그램: Slack
