<h1>Wecode 35기 1차 프로젝트 - 1팀 LOCTEA - Part.김익현</h1>

![스크린샷 2022-07-29 오후 4 58 12](https://user-images.githubusercontent.com/106301980/181713092-f83ac4cb-9098-484a-8afe-7141db81fce7.png)


<h2>개요</h2>
<ul>
  <li>오설록 웹페이지 클론코딩 프로젝트</li>
  <li>프로젝트는 2주동안 진행되며, 1주차에는 필수 구현사항 위주로 아래 항목들을 구현하였습니다.
    <ul>
      <li>Nav, Footer</li>
      <li>메인페이지</li>
      <li>상품 목록</li>
      <li>상품 상세</li>
      <li>장바구니</li>
      <li>로그인, 회원가입</li>
    </ul>
  </li>
  <li>2주차에는 추가 구현사항과 코드 리팩토링, 서버 통신 위주로 진행하였습니다.
    <ul>
      <li>주문서 작성</li>
      <li>로그인, 회원가입 시 비밀번호 확인 가능 기능 구현</li>
      <li>라이브러리 사용 없이 슬라이드 구현</li>
      <li>로그아웃</li>
    </ul>
  </li>
</ul><br>

<h2>팀원</h2>
<strong>Front-end</strong><br>
- 김익현, 류승연, 이금관, 최재홍<br>
<strong>Back-end</strong><br>
- 박정용, 조민지, 조예슬<br><br>

<h2>사용한 기술</h2>
<strong>Front-end</strong><br>
- HTML, CSS(SASS), Javascript, React<br>
<strong>Back-end</strong><br>
- Django, Python, MySQL, AWS(RDS, EC2), Bcrypt, JWT, django-cors<br>
<strong>Cowork</strong><br>
- Git, Slack, Trello<br><br>

<h2>구현 기능</h2>

  Main Page, Item Detail, Order (김익현)
   - CSS 애니메이션을 이용한 공지사항 구현
   ![화면_기록_2022-07-29_오후_5_15_06_AdobeExpress](https://user-images.githubusercontent.com/101634412/182009945-b55aa15f-9bbe-4432-86ff-0fa5b67106f3.gif)
  
   - 라이브러리를 사용하지 않고 useState를 활용한 무한 슬라이드 구현
   ![화면_기록_2022-07-29_오후_5_15_29_AdobeExpress](https://user-images.githubusercontent.com/101634412/182010040-82f5be1c-2b6d-4d5a-9467-b11723faeb17.gif)

   - 각 조건에 따른 조건부 렌더링을 통해 할인 가격 및 재고 여부에 따른 일시품절, 바로구매/장바구니로 이동 가능한 상품 상세 페이지 구현
   ![화면_기록_2022-07-29_오후_5_21_28_AdobeExpress](https://user-images.githubusercontent.com/101634412/182010292-cf899f4b-8102-444d-9f01-373a9e92f8c2.gif)

   - new Date() 함수를 이용해서 거꾸로 시간이 줄어드는 로직 구현
   ![화면_기록_2022-07-29_오후_5_15_53_AdobeExpress](https://user-images.githubusercontent.com/101634412/182010079-8341033b-9c1d-4d5a-910f-588322125911.gif)
 
   - CSS호버 기능을 통해 마우스 호버시 밑에서 올라오는 애니메이션 구현
   ![화면_기록_2022-07-29_오후_5_16_20_AdobeExpress](https://user-images.githubusercontent.com/101634412/182010261-293404b8-1747-43a8-ae57-b12959eb9bb8.gif)
   
   - Cart 페이지에서 fetch(method:"PATCH,DELETE") 함수를 활용하여 BE와 통신 가능하도록 하여 상품 삭제 및 수량 변경 등의 기능을 구현 
   ![화면_기록_2022-07-29_오후_5_22_42_AdobeExpress](https://user-images.githubusercontent.com/101634412/182010282-572c0ee1-5777-49cb-a585-4ada7f9a1ef3.gif)

     
