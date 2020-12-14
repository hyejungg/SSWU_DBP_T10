# 전국공중화장실현황
2020-2 SSWU DBP-T10 기말과제
(20160530 이지연, 20172049 백지우, 20180971 김연서, 20180977 김혜정)

## :exclamation: 홈페이지 링크
http://dbpt10.dothome.co.kr/final/intro.html

//최종코드 final 폴더 + images 폴더

## :exclamation: 홈페이지 소개
<img width="960" alt="intro" src="https://user-images.githubusercontent.com/70576313/102041089-d7c04400-3e11-11eb-9d54-8ad111d5aa97.png"> 
<img width="960" alt="index" src="https://user-images.githubusercontent.com/70576313/102040997-a3e51e80-3e11-11eb-9e09-c9118b6c5e4e.png">
<img width="960" alt="select" src="https://user-images.githubusercontent.com/70576313/102041117-e73f8d00-3e11-11eb-93d7-2ab0cb819c3a.png"> 
<img width="960" alt="search_city" src="https://user-images.githubusercontent.com/70576313/102041132-f1fa2200-3e11-11eb-9b64-9a30dfe278b3.png">
<img width="960" alt="search_gu" src="https://user-images.githubusercontent.com/70576313/102041140-f8889980-3e11-11eb-92c7-ef7785c8f184.png">
<img width="960" alt="res" src="https://user-images.githubusercontent.com/70576313/102041151-fde5e400-3e11-11eb-85df-f28f44aeb80f.png">


## :exclamation: 개발과정 및 역할분담
- 1차 회의(201125)
```
//참석자 : 김연서, 김혜정, 이지연
1. 주제 선정
- 공중화장실 정보 보여주는 사이트
  * 남녀 구분
  * 지도 띄워놓고 -> 지역 선택하면 상세 정보 띄우는 식으로 구현
  
2. 주제 구체화
- 주제 : 공중화장실
- 목적 : 생활 중 화장실을 찾아갔을 때 공용을 원치 않았지만, 공용화장실인 경우가 종종 있다. 이런 불편한 상황을 없애고 싶다.
- 보여줄 내용 : 
  (1) 화장실 위치(전국 지도) + 주소 포함
  (2) 남녀공용여부
  (3) 영업시간, 전화번호 관리기관명
  (4) 장애인 + 어린이용 유무
  
3. 해야할 일
- T10 github 저장소 만들기
- 다음 회의 일정 : 11/28, 11-13시 Zoom //변동 가능

4. 개발 환경 선정
- Database : MySQL
- 프론트엔드 언어 : HTML, CSS, JavaScript
- 백엔드 언어 : PHP
```
- 2차 회의(201129)
```
//참석자 : 김연서, 김혜정, 이지연, 백지우

1. 주제 확정
- 공중화장실 정보 보여주는 사이트

2. 역할 분담
#지연, 지우
- 지도 & 지도 테이블 구현
#연서, 혜정
- 화장실 정보 표 형식으로 보이기
- 검색 + 페이징 기능 구현

3. 해야할 일
- 개발 진행
- 다음 회의 일정 : 12/4, 13시 Zoom

```
- 3차 회의(201204)
```
//참석자 : 김연서, 김혜정, 이지연, 백지우
1. 진행 확인
#지연, 지우
- 지도 틀 만든 상태
- db 연결 -> db 정보 띄워야 함
- 지도 누르면 화장실 목록 나오게 해야함

#연서, 혜정
- 페이징 구현 완료
- 장애인 여부, 어린이전용 칼럼 추가해야 함
- 호스팅 해야함

2. 해야할 일
- 미해결된 부분 해결하기
- 미완성된 부분 완성하기
- 호스팅 완료하기
- 다음 회의 일정 : 12/11, 20시 Zoom
```
- 4차 회의
```
//참여자: 김연서, 김혜정, 이지연, 백지우
1. 진행 확인
#지연, 지우
- 지도 틀 만든 상태
- 지도 누르면 화장실 목록 나오게 해야함

#연서, 혜정
- 페이징 오류 수정 완료
- 호스팅 완료
- 호스팅 후 테이블 변경 사항 안내

2. 해야할 일
- 소개페이지 완성
#지연 : 지도 누르면 -> 이름 바뀌게, 한줄 소감 작성 
#지우 : 버튼 클릭시 -> 테이블에 화장실 정보 보이게, 한줄 소감 작성 
#연서 : 페이징 테이블 css 적용하기, 한줄 소감 작성
#혜정 : 웹서버에 db import 완료, 코드 병합 + 호스팅 서버에 파일 올리기, 한줄 소감 작성
- 다음 회의 일정 : 12/14, 15시 Zoom (변동 가능)
```
각 개발 과정에 대한 회의록 전문 
https://docs.google.com/document/d/1e8HGwMeWKJhhNpcsvZtUjkGENvkqhnQ0oDc9zJjqaZc/edit


