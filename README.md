# :book: 수험생을 위한, 문제집 추천 서비스
#### backend 작업할 때 사용했던 레포지토리가 private로 되어있고, 저한테 권한이 없어서 개인 레포로 옮겨왔습니다.

### :pushpin: 프로젝트 기간 : 2022년 3월 28일 ~ 2022년 5월 28일

### :pushpin: Team : 에잇
- <p> 백엔드 : 양유림, 최혜영 </p>
- <p> 프론트엔드 : 김가은, 정현우 </p>
- <p> 기획 : 배정은, 윤서연, 윤지원 </p>
- <p> 디자인 : 양의진 </p>


### :pushpin: Description
“문제집 제대로 지르자” <문제지(Munjezi)>는 수능 문제집 리뷰 및 탐색 플랫폼(웹)이다. 난이도와 평가기준을 포함한 과목별 태그와 유저의 성적을 적용하여 문제집을 필터 링하는 방식으로 수능 문제집에 특화된 탐색 경험을 제공한다. 유저의 문제집 리뷰 작성
건수가 누적되면 실물 문제집 보상 신청이 가능하다. 리뷰는 문제집 필터링 및 커뮤니티 형성에 기여하여 서비스 정체성으로서 기능한다.

### :pushpin: 아이템 포스터
<img src = "https://user-images.githubusercontent.com/56334375/234221794-ed36919a-590d-40e5-a7be-4de7341f2d8e.jpeg">

### :pushpin: Development Environment & Language
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white"/></a>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/></a>

### :pushpin: Feature
- 로그인/회원가입

- 마이페이지
  - 리뷰 작성으로 받은 포인트 관리
  - 개인 성적 정보 관리
  
- 필터링을 통한 문제집 추천 서비스
  - 과목별 세부 태그 : 공통태그 외에, '문제지 태그'를 이용해서 사용자들이 과목 특성에 따른 태그를 이용하여 과목별 맞춤 추천을 받을 수 있음
  - 문제집 저장 : 추천받은 문제집을 미리보기에서 바로 저장할 수 있는 버튼을 통해 추후 사용자가 저장된 문제집에서 리스트를 확인하고, 문제집 비교 서비스를 간편하게 확인 가능
  - 문제집 세부 정보 : 지은이/출판사/가격 등의 정보를 상세정보로 제공하여 사용자가 문제지 사이트 내에서 문제집에 관한 정보 알 수 있도록
  - 많이 푼 문제집 : 문제집을 리뷰한 사용자의 유저데이터를 통해 연관 문제집을 보여줌으로써 사용자에게 2차 추천 서비스를 제공한다.
  
- 리뷰
  - 성적별 맞춤 난의도 리뷰
  - 리뷰 작성자의 성적 정보 제공
 
- MY 뉴스
  - 회원별 조회/스크랩 목록 조회
  - 회원별 추천 뉴스(성별에 따라)
  - 조회 목록 삭제
  
<img src="https://user-images.githubusercontent.com/56334375/234219787-b97b1d42-0485-428d-8697-a904785bab24.mp4">

### :pushpin: ERD

<img src="https://user-images.githubusercontent.com/56334375/234220183-d7a041f3-5244-4c27-9833-0cb96522edb1.png">
