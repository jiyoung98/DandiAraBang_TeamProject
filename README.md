<h1>단디알아방</h1>
</br>
<p></p>
<p>이 레포지토리는 단디알아방 팀원 한지영(jiyoung98)의 복사본입니다! 원본은-> https://github.com/pirogramming/DD_AraBang</p>

## 1. 서비스 소개 
<p>자취방/ 하숙집 사용후기 공유 커뮤니티 서비스</p>
</br>

## 2. server
<p>framework :django</p>
<p>language: javascript, python, JQuery </p>
</br>
</br>

## 3. Database
SQLite
</br>
</br>

## 4. Preview
![image](https://user-images.githubusercontent.com/61833149/91725161-4bc73b00-ebd9-11ea-9046-69173802e2b8.png)

![image](https://user-images.githubusercontent.com/61833149/91725188-55e93980-ebd9-11ea-8687-f7f2a6e857d3.png)

![image](https://user-images.githubusercontent.com/61833149/91725504-cee89100-ebd9-11ea-9eae-d4c1bb083ef9.png)

![image](https://user-images.githubusercontent.com/61833149/91725538-d9a32600-ebd9-11ea-9263-289ede3fe52b.png)

![image](https://user-images.githubusercontent.com/61833149/91725233-67cadc80-ebd9-11ea-85fb-f3c303057de1.png)

![image](https://user-images.githubusercontent.com/61833149/91725266-73b69e80-ebd9-11ea-99d7-1644922c8b4b.png)

![image](https://user-images.githubusercontent.com/61833149/91725305-829d5100-ebd9-11ea-9585-57fa00ca8c32.png)

![image](https://user-images.githubusercontent.com/61833149/91725356-95b02100-ebd9-11ea-9691-42395a8d235e.png)

![image](https://user-images.githubusercontent.com/61833149/91725390-a2cd1000-ebd9-11ea-90b7-b0454ae8d4c2.png)

![image](https://user-images.githubusercontent.com/61833149/91725433-b1b3c280-ebd9-11ea-906e-ca4c39cade4c.png)

![image](https://user-images.githubusercontent.com/61833149/91725468-c09a7500-ebd9-11ea-8c8b-25d8d5218f26.png)

![image](https://user-images.githubusercontent.com/61833149/91725561-e0ca3400-ebd9-11ea-89c9-1d5f7147fc46.png)

![image](https://user-images.githubusercontent.com/61833149/91725576-e889d880-ebd9-11ea-9803-3cc742aa9228.png)

![image](https://user-images.githubusercontent.com/61833149/91725604-f17aaa00-ebd9-11ea-82e4-fe35d135fd17.png)

![image](https://user-images.githubusercontent.com/61833149/91725625-f93a4e80-ebd9-11ea-8a29-b941720acc04.png)

![image](https://user-images.githubusercontent.com/61833149/91725649-01928980-ebda-11ea-8d5b-207506b92e1e.png)

![image](https://user-images.githubusercontent.com/61833149/91725728-1bcc6780-ebda-11ea-9af8-b73d565ba6c2.png)

![image](https://user-images.githubusercontent.com/61833149/91725777-28e95680-ebda-11ea-8685-3e8c2a92325e.png)



## 5. 서비스 주요기능

* ### 1. mainpage
<p>- 서비스 상세설명</p>
<p>- 주요 기능(회원정보/거주후기/커뮤니티)으로 이동하는 고정 메뉴바</p>
<p></p>
<img width="752" alt="img" src="https://user-images.githubusercontent.com/65646971/90869552-5c0a3980-e3d3-11ea-927f-0dd358050a75.PNG"></br>

* ### 2. user
<h5>2-1 ) 기본 회원정보</h5>
  <p>- 로그인: 학교 이메일을 아이디로 사용</p>
  <p>- 회원가입: 학교정보 입력 + (학교 이메일 인증)</p>
<h5>2-2 ) 마이페이지</h5>
  <p>- 회원정보: 회원정보 수정, 회원탈퇴</p>
  <p>- 땅문서 개수 확인</p>
  <p>- 거주후기: 내가 쓴 거주후기 확인, 새로운 거주후기 작성</p>
<p></p></br>

* ### 3. review
<p>- 거주 후기 지도: 지도에서 학교 선택</p>
<p>- 거주 후기 열람: 지도 확대 축소에 따라 리로딩, 학교 선택 후 지도 화면 안에 위치한 거주 후기만 열람 가능, 지도에서 장소 선택 시 해당 장소 거주 후기 수와 해당 거주 후기 글들 강조됨, 후기 열람을 위한 땅문서 여부나 로그인 여부에 따라 confirm(선택창)을 통해 열람 여부 결정</p>
<p>- 거주 후기 작성: Daum 주소검색 서비스가 연동된 주소 등록 기능, 사진과 함께 거주후기 작성 및 등록, 필수 항목 전체 작성 안 하면 alert, 거주 후기 수정 및 삭제 기능</p>
<p></p></br>

* ### 4. community
<p>- 전체 게시판: 학교에 상관없이 모든 이용자들이 사용 가능한 커뮤니티</p>
<p>- 학교 게시판: (인증한 학교 게시판만 열람 가능한 커뮤니티)</p>
<p>- 상세 게시판: 자유토킹방, 정보나눠방, 사고팔아방, 같이시켜방</p>
<p>- 게시판 기능</p>
<p>  : 글 작성, 글 수정 및 삭제, 댓글 입력, 댓글 수정 및 삭제</p>
<p>  : 내가 쓴 글 목록, 내가 좋아요 누른 글 목록</p>
<p>  : 게시판 키워드 검색, 실시간 인기글(좋아요 순으로 정렬)<p>
<p></p></br>

* ### 5. user 땅문서 제도(포인트 제도) : 신뢰도 있는 거주후기 작성 및 열람 서비스를 위한 제도
<p>- 회원가입 시 10개 제공</p>
<p>- review: 거주 후기 열람 시 3개 차감, 거주 후기 작성 및 등록 시 10개 제공</p>
<p>- community: 글 작성 시 1개 제공</p>
<p></p> 
</br>
</br>
  
## 6. 팀원소개
 <img width="752" alt="img" src="https://user-images.githubusercontent.com/65646971/90873543-47c93b00-e3d9-11ea-956e-bb2dc69dc36b.PNG">  
