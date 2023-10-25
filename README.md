# ProJect CrimeSecurityWeb
![rect](https://capsule-render.vercel.app/api?type=rect&color=gradient&text=%20%20CSW%20%20&fontAlign=30&fontSize=30&textBg=true&desc=Crime%20Security%20Web&descAlign=60&descAlignY=50)

## 🛠 Stacks

- Front
  
![HTML5](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)

- Back
  
![Java](https://img.shields.io/badge/Java-007396.svg?&style=for-the-badge&logo=Java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F.svg?&style=for-the-badge&logo=Spring&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000.svg?&style=for-the-badge&logo=Oracle&logoColor=white)

<br>

## 📋 ERD
![image](https://github.com/kimm9803/CrimeSecurityWeb/assets/118273341/5207ae9d-f140-4db7-998e-09dba0ffb2ea)
Noction Link
https://rumbling-drizzle-f3c.notion.site/CrimeSecurityWeb-2023-09-2023-10-cea7c4b1dbd24ac48931ed4c186e3499?pvs=4

## 👨‍👦‍👦 팀원
3명 - 김현수, 권준민, 전민진

## 📚 프로젝트 소개
최근 이슈가 된 불특정 다수를 대상으로 하는 범죄들의 증가와 이에 따른 호신용품과 호신술 등 자신의 안전에 대한 관심이 상승하는 것을 토대로 **커뮤니티와 쇼핑몰**을 합친 사이트를 기획

## 📚 프로젝트 주요 기능


▶ **게시판 별 기능을 구현**

- 자유게시판 & 지역 별 게시판 : 게시물 CRUD , 댓글 기능(수정, 삭제) , 추천 기능
- 공지사항 : 공지사항 CRUD , 공지사항은 자유게시판 & 지역 별 게시판 상위 고정
- Q&A 게시판 : 질문 · 답변 CRUD , 질문은 회원만 답변은 관리자만 가능

▶ **공공데이터** **Open API 를 활용하여 표와 차트 구성**

- 지역 별 클릭 기능 구현이 가능하도록 SVG파일 수정
- 공공 데이터 OpenAPI를 활용하여 JSON데이터 추출
- 지역별 범죄데이터 와 Chart.js를 활용하여 차트 작성

▶ **쇼핑몰 기능 구현**

- 상품 등록, 삭제는 관리자가 가능 / 회원은 구매 후 리뷰 작성 가능
- 장바구니 페이지에서 선택 주문, 전체 주문 가능 하도록 기능 구현
- 카카오페이, 토스페이, 신용카드 결제 API를 사용하여 결제 기능 구현
- 결제 시 포인트 적립, 포인트 사용 가능

## 👨‍👦‍👦 담당 기능

### **API 활용 표 / 차트 구현**

- 공공데이터 OpenAPI를 활용해 전국 5대범죄 JSON 데이터를 지역 별로 필터
- 추출해낸 데이터를 기반으로 지역 별 범죄 발생건수, 검거율을 표와 차트로 보기 쉽게 구현
- 차트 구현시 Chart.js 활용

### 자유게시판 / 지역 별 커뮤니티 화면 · 기능 구현

- 커뮤니티 게시글 CRUD / 댓글 CRUD / 글 추천 기능
- 커뮤니티의 글 목록 조회 시 페이징, 검색, 정렬 기능 구현

### 공지사항 구현

- 공지사항 CRUD / 공지사항 등록 시 마감일 입력하여 마감일 경과 게시물 조회 X
- 커뮤니티 글 목록 조회 시 공지사항은 항상 글 상단에 고정

### 마이페이지 · 관리자 페이지 화면 구현

- 마이페이지의 작성한 게시물, 댓글,추천한 게시물의 수와 목록을 화면에 구현
- 관리자 페이지의 커뮤니티 카테고리 관리 / 공지사항 관리 구현

## 💡 성장한 부분 / 느낀점

 비전공자로 프로그래밍을 배우고 난 후 첫 프로젝트였기 때문에 결과물을 낼 수 있을지 의문을 가지고 있었지만 결과물이 만들어지는 것을 경험하고 자신감을 가지게 되어 다음 프로젝트에는 좀 더 주도적으로 프로젝트를 진행할 수 있을 것 같다.

 공공데이터 OpenAPI를 사용하면서 JSON 형식의 데이터를 추출하는 경험을 처음 해 익숙하지 않아 어려움을 겪었지만 이해를 하고 나니 수월하게 데이터를 추출할 수 있게 되었다.
이후 프로젝트 또는 업무에 JSON 데이터를 추출해야할 때 효율적이게 수행할 수 있을 것 같다.
