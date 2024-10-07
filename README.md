# :memo:스프링부트 쇼핑몰 프로젝트 README
</div>
  <div style="font-weight: 700; font-size: 15px; text-align:left;">
      <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🔍️프로젝트 소개</h2>
        ●&nbsp;     스프링부트를 사용해 쇼핑몰 프로젝트를 구현하였습니다. 카카오 로그인, 결제 시스템 등 여러가지 기능을 구현해보았습니다.<br>
        ●&nbsp;     원하시는 옷의 재고 확인 및 주문하는 온라인 쇼핑몰 웹사이트입니다.<br>
        ●&nbsp;     여행을 즐기면서 시간을 절약하고 알찬 여행이 되게끔 도움을 줄 수 있습니다.<br>
        ●&nbsp;     여행지에 대한 정보를 공유 할 수 있는 게시판을 통해 유용한 정보를 얻을 수 있습니다.<br><br>
        &nbsp;&nbsp;&nbsp;&nbsp;<b>프로젝트 진행기간 : 24/06/24 ~ 24/07/05(12d)</b>
    </div>
    </div>
        <div align= "left">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ 개발 환경 </h2> 
     <div style="margin: 0 auto; text-align: center;" align= "left"> <img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=for-the-badge&logo=Apache Tomcat&logoColor=white">
          <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">
          <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white">
          <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
          <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white">
          <br/><img src="https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white">
          <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
          <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white">
          <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white">
          <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"><br><br>
        ●&nbsp; Language : <code>JAVA(11)</code>,<code>JavaScript(1.5)</code><br>
        ●&nbsp; Database : <code>MySQL(8.0.36)</code><br>
        ●&nbsp; API : <code>네이버 API</code>, <code>구글 맵 API</code>, <code>포트 원 API</code>, <code>coolSMS</code>, <code>카카오 로그인 API</code><br>
        ●&nbsp; Library & Framework : <code>Springboot(2.x)</code>, <code>Spring Security(5.2.7)</code><br>
          <br/></div><br>
          <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> :pushpin: 맡은 역할 </h2>
         <b>임재현</b><br>
         &nbsp;&nbsp;&nbsp;●&nbsp; DB설계, 메인페이지,헤더, 모든 페이지CSS, 카카오 로그인, 상품관리 및 결제<br><br>
         <b>김혁</b><br>
         &nbsp;&nbsp;&nbsp;●&nbsp; DB설계, 회원관리 구성, 이메일 인증, ERD<br><br>
         <b>이민석</b><br>
         <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> :white_check_mark: 주요 기능 </h2>
         <b>로그인</b><br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 회원가입시 이메일 인증<br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 카카오 로그인<br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 인증을 통한 아이디 및 비밀번호 찾기<br><br>
          <b>상품관리</b><br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 관리자 로그인시 상품 및 재고수량 등록<br><br>
          <b>상품 결제</b><br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 장바구니 담기 및 장바구니 내 결제<br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 원하는 상품의 재고가 남아있을 시 결제<br><br>
           <b>마이페이지</b><br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 개인정보 수정<br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 결제한 상품내역 확인 및 취소<br><br>
           <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 💡 설계 및 기능구현 </h2>
          
  ### ER-다이어그램<br> 
<img src="https://github.com/user-attachments/assets/13cf07b1-b6b7-4996-9e64-20163deada69" width="1450" heigt="420"><br><br>

 # 메인 화면
 <img src="https://github.com/user-attachments/assets/90f7feba-3cf2-4a32-b56f-8017ea4b1586" width="1450" heigt="400"><br><br>
 
 # 로그인 화면
 <img src="https://github.com/user-attachments/assets/bac8cbdc-eeb6-4f37-936d-c03a26abe620" width="1450" height="440"><br><br>

 # 회원가입
 <img src="https://github.com/user-attachments/assets/45eb79fa-366e-40b6-8591-e68e82663b4f" width="1450" height="510">
 
 <img src="https://github.com/user-attachments/assets/8c547b10-dbdb-4e2c-9a25-9d62f6163175" width="1450" height="560"><br><br>

 # 개인정보 확인
<img src="https://github.com/user-attachments/assets/c050efbc-9111-483d-a3b9-a1fad364625c" width="1450" height="440"><br><br>

 # 개인정보 수정
<img src="https://github.com/user-attachments/assets/80b96146-d62e-4e90-8b82-23eb5aadaaca" width="1450" height="540"><br><br>

 # 비밀번호 변경
<img src="https://github.com/user-attachments/assets/b1048fa1-09b7-4569-8e38-1f92d552495e" width="1450" height="460"><br><br>

 # (관리자)상품 등록 
 <img src="https://github.com/user-attachments/assets/3264a018-4c09-4fca-be8c-ffe73eb33e24" width="1450" height="470"><br><br>

 # 상품 정보 확인
 <img src="https://github.com/user-attachments/assets/b64b8af6-5d53-405c-99d2-ff689fac8f53" width="1450" height="540"><br><br>

 # 상품 주문
 <img src="https://github.com/user-attachments/assets/da63370a-f61c-44c5-823e-1366eebc8300" width="1450" height="500"><br><br>

 # 장바구니
 <img src="https://github.com/user-attachments/assets/bcee43ee-2e9f-438d-a590-1b88a85ee883" width="1450" height="540"><br><br>

 # 주문 및 결제
 <img src="https://github.com/user-attachments/assets/5749137c-a5eb-45c5-84dc-0654b3a46511" width="1450" height="540"><br><br>

<div>
     <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 	:zap: 미구현 기능 </h2>
     ●&nbsp;     상품 평점 기능<br>
     ●&nbsp;     상품 상세 디테일 부분<br>
     ●&nbsp;     카테고리 기능<br>
     </div>
