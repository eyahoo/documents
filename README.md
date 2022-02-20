

# 📁 Photo-log
## 프로젝트 이름 : Photo-log
<br>

## 👩‍💻 팀원소개
#### • 허강주(PM & Backend) : 회원 가입 및 로그인 구현,DB 모델링
#### • 박채연(Frontend) : Front 디자인, Map 페이지 구현
<br>

## 📚 프로젝트 설명 :
### <strong> 1. Record memories in map<br> </strong>
날짜 별로 기록하는 사진첩은 많지만, 친구/가족/연인과 어디서 무엇을 했는지 기록할 수 있는 앱은 현존하지 않아 신규 런칭하고자 합니다.

### <strong> 2. Group by group<br>  </strong>
친구/가족/연인 모임 별로 다른 지도를 만들어 추억을 모임 별로 공유할 수 있습니다.

### <strong> 3. Personalization<br>  </strong>
Category(운동/맛집/여행..) 별로 사용자 개인이 일기처럼 지도를 활용할 수 있습니다.
<br><br>


## 📝 사용언어, 기술스택
![Generic badge](https://img.shields.io/badge/platform-Web-brightgreen.svg) ![Generic badge](https://img.shields.io/badge/library-React-blue.svg) ![Generic badge](https://img.shields.io/badge/framework-NestJS-green.svg)
![Generic badge](https://img.shields.io/badge/database-MongoDB-yellow.svg) ![Generic badge](https://img.shields.io/badge/api-mapbox-red,.svg) ![Generic badge](https://img.shields.io/badge/language-TypeScript-important.svg)
<br>

 
## 💼 필요한 기능
- [ ] 로그인 & 회원가입
- [ ] 마이페이지
    - [ ] 개인정보 수정
    - [ ] relation-ship setting
        - [ ] Create
        - [ ] Delete
        - [ ] Update
        - [ ] Read
    - [ ] invite
        - [ ] 링크 입력한 이메일로 보내기
    - [ ] delete account
        - [ ] 회원 탈퇴
    - [ ] sign-out
    - [ ] disconnect-relation
        - [ ] 모임 탈퇴
    - [ ] remove all data
        - [ ] 모임장일 경우에만 삭제 가능
    - [ ] etc..
- [ ] 사진 업로드
    - [ ] 카메라 ( 앱 내에서 촬영시 자동으로 위치, 시간 등록 )
        - [ ] 앨범에서 선택 / 촬영
        - [ ] TODO : 권한 ( 카메라, 위치 ) 어떻게 얻어올지?
            - [ ] https://stackoverflow.com/questions/19414031/accessing-camera-roll-from-browser-in-ios
            - [ ] 브라우저에서 권한 요청하는 경우 조사
            - [ ] 카메라/위치 정보 접근 허용 ( iPhone 기능) 
    - [ ] 앨범에서 업로드 ( 메모나 간단한 텍스트 작성 가능하게 )
- [ ] 지도 뷰
    - [ ] 기본으로 로딩되는 페이지는 사용자 설정으로 하기
        - [ ] 첫 기록을 기준으로 OR 마지막 기록을 기준으로
    - [ ] 마커 클릭시 해당 지역에서 찍은 사진 및 기록 리스트로 보여주기
        - [ ] 같은 장소에 다른 데이터가 있는 경우
            - [ ] 2022/10/22
            - [ ] 	A
            - [ ] 	B
            - [ ] 	C
            - [ ] 2022/11/22
            - [ ] 	A
            - [ ] 	B
            - [ ] 	C 
    - [ ] 해당 리스트에서 사진 및 기록 수정 & 삭제 가능할 것
    - [ ] 모임 선택 => 모임 별 map 지도 뷰
- [ ] 메뉴 구성
    - [ ] Create Record
        - [ ] Drag/Click 으로도 가능하게

    - [ ] Select Organization


<!-- ### Maven
| 패키지명 | 버전 | 설명 |
| -------- | ---- | ---- |
| Swagger | ![Generic badge](https://img.shields.io/badge/release-2.8.0-blue.svg)| 팀용 API 문서 및 디자인 도구 |
| JUnit4 | ![Generic badge](https://img.shields.io/badge/release-4.7.1-blue.svg)| 단위 테스트 프레임 워크 |
| Rombok | ![Generic badge](https://img.shields.io/badge/release-1.18.12-blue.svg)| 모델 데이터 객체 최소화 |
| Nurigo | ![Generic badge](https://img.shields.io/badge/release-2.2.1-blue.svg)| 문자메세지 자동 전송 |
| Ojdbc6 | ![Generic badge](https://img.shields.io/badge/release-11.2.0.1.0-blue.svg)| 오라클 데이터베이스 |
| Tomcat | ![Generic badge](https://img.shields.io/badge/release-9.0.36-blue.svg)| 웹 어플리케이션 서버 | -->
<br>

<!-- ## 📜 Data Model Diagram
![KakaoTalk_20200930_153857747](https://user-images.githubusercontent.com/68583697/94651283-2f7f0100-0333-11eb-9093-fcb7d5aafb65.png)
<br>
Member : 사용자 <br>
Class : 개설된 반 <br>
Store : 등록되어 있는 가게 <br>
Waiting : 현재 진행중인 주문 <br>
<br><br>

## 프로젝트 구조
|BackEnd|FrontEnd|
|------|---|
|![캡처](https://user-images.githubusercontent.com/68583697/94669084-c22b9a00-034b-11eb-93e2-a676e2f07368.PNG)|![캡처2](https://user-images.githubusercontent.com/68583697/94669086-c22b9a00-034b-11eb-822b-8852db63051c.PNG)|
<br>



## 💻 최종 실행 화면
<details>
<summary>메인화면</summary>
<div markdown="1">
  
 ![FireShot Capture 012 - chaeyeon - localhost](https://user-images.githubusercontent.com/68583697/94666502-83481500-0348-11eb-80e4-ed9dd1109d22.png)
 
</div>
</details>

<details>
<summary>회원가입 화면</summary>
<div markdown="1">
  
![1](https://user-images.githubusercontent.com/68583697/94666879-ff425d00-0348-11eb-8ad7-4c5402790bd5.png)
 
</div>
</details>

<details>
<summary>모집하기</summary>
<div markdown="1">
  
![2](https://user-images.githubusercontent.com/68583697/94667026-387acd00-0349-11eb-9a6f-2182816f4adc.png)
 
</div>
</details>

<details>
<summary>등록하기</summary>
<div markdown="1">
  
![KakaoTalk_20200930_175651163](https://user-images.githubusercontent.com/68583697/94667114-547e6e80-0349-11eb-8b2e-a91f8b4ac7ef.png)
 
</div>
</details>

<details>
<summary>마이페이지</summary>
<div markdown="1">
  
![KakaoTalk_20200930_175808855](https://user-images.githubusercontent.com/68583697/94667165-65c77b00-0349-11eb-9f0e-81fbea8a85a5.png)

</div>
</details>
<br>

## 🔎 Data Model Diagram - 변경사항 2020-09-08
- 멤버 테이블 마감시간, 수령장소, 최소가격, 최소인원, 상세설명 추가 
- WAIT_MINPERSON 이랑 WAIT_MINLIMIT 이랑 동일 -> WAIT_MINLIMIT 삭제예정 (작업중)
## 🔎 Data Model Diagram - 변경사항 2020-09-07
- 멤버 핸드폰 번호 추가
- 호스트도 waiting_mems 에 들어감
- waiting 테이블에 현재 대기자 인원 추가 -->
