# EnjoyTrip!

<p align="center">
  <br>
  <img src="https://velog.velcdn.com/images/joajy/post/c0778352-4818-4302-90f7-97e5d6243220/image.png">
  <br>
</p>

## 개선된 요구 사항 목록

### :notebook_with_decorative_cover: User
  * 회원 가입
  * 이메일 중복 체크 기능
     * 이메일 중복 체크 이후 변경 시 다시 체크 알람 팝업
     * 이메일 중복 체크 실패 시 회원 가입 제한
  * 로그인
  * 로그아웃
    * 로그아웃 시 메인 페이지로 이동
  * 회원 정보
    * 회원 정보 확인
    * 회원 정보 수정
    * 회원 아이디 찾기
    * 회원 비밀번호 찾기
    * 회원 탈퇴

### :orange_book: Board
  * 글 작성
  * 전체 글 리스트 조회
    * 페이징(10페이지 단위)
  * 작성된 글 조회
  * 조회수 기능
  * 작성자 표기
<br/>

### :ledger: Trip
  * 시/도 설정
  * 시/도 및 키워드를 통한 검색
  * 각 장소의 분류 별 마커 차별화
  * 상세 페이지 조회
    * 상세 페이지 사진 출력
    * 상세 페이지 데이터 출력
    * 상세 페이지 맵 출력
    * 서치 페이지 맵 출력
  * 핫플레이스 등록 페이지 이동

### :blue_book: HotPlace
  * 핫 플레이스 등록 페이지
    * 핫 플레이스 맵 출력
    * 핫 플레이스 사진 등록
  * 핫 플레이스 리스트
    * 사진 출력
    * 상세 페이지 이동 및 방문 위치 출력
    * 페이징(10페이지 단위)
  * 핫 플레이스 정보 수정
  * 핫 플레이스 정보 삭제

## 개선된 ERD Diagram
![image](https://github.com/Joajy/AlgoStudy/assets/86274253/39c472ad-8710-4c39-8e43-122605ca3c25)

## 개선된 Class Diagram

## 동작 화면

<h3>1. User</h3>
   1-1. Sign Up
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/3e20a253-ed13-4883-969d-d6deaa3647d5">
    </p>
   1-2. Log In & Log Out
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/28f210da-9632-4470-8796-46cd75625eda">
    </p>
    1-3. Information Find
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/68fbefd2-8f51-4e7d-a790-a9455c32bac5">
    </p>
    1-4. Information Modify & Delete
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/3acbafb4-2dd5-42a1-bf53-4c9d56c16382">
    </p>
    1-5. Modify User's HotPlace
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/d0500096-f6c3-416d-9940-4e4a816b8193">
    </p>
    1-6. Delete User's HotPlace
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/7e4f7fc8-afa2-479f-8740-df96fbe1e5f4">
    </p>
    1-7. My Posts' List Up
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/60c9b9c3-759d-4f8d-b05d-9ee44da42bf1">
    </p>
    
<br><hr>
   
<h3>2. Board</h3>
  2-1. View Board List & Write with Paging
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/b294dd10-fd54-4ebb-9455-faa6c97a54dd">
    </p>
     2-2. Board Detail -> ViewCount, Writer
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/ecd377c5-67ec-48ab-bc81-7d72c3c184bd">
    </p>
    <br><hr>

<h3>3. Trip & HotPlace </h3>
  3-1. Travel Map on Trip Page
   <p align="center">
     <img src="https://github.com/Joajy/Algorithm_BOJ/assets/86274253/42578e0e-e95d-4532-a29c-ec53ee060dfa">
    </p>
  3-2. Search With Tag & Without KeyWord
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/ecd8c4b3-27a1-4d1c-8ce3-3a95cd993d3b">
    </p>
  3-3. Search With Tag & KeyWord
   <p align="center">
     <img src="https://github.com/Joajy/Algorithm_BOJ/assets/86274253/d9583b95-2905-40f1-bb3f-3cc3bead720b">
    </p>
  3-4. Register HotPlace
   <p align="center">
       <img src="https://github.com/Joajy/Algorithm_BOJ/assets/86274253/9f6f27da-567e-4253-898e-c42422a0026a">
    </p>
  3-5. HotPlace List & Detail
   <p align="center">
     <img src="https://github.com/Joajy/RepoForUploadImageIntoIssues/assets/86274253/2290555a-eb39-4690-b618-744f7487a054">
  </p>
    <br><hr>
    
<!-- Stack Icon Refernces -->

[js]: /images/stack/javascript.svg
[ts]: /images/stack/typescript.svg
[react]: /images/stack/react.svg
[node]: /images/stack/node.svg
