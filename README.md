# 팀글벙글
팀글벙글은 프로젝트 일정 관리를 효율적으로 할 수 있도록 도와주는 협업 툴입니다.   
다양한 기능을 통해 팀원 간의 소통과 작업 관리를 원활하게 진행할 수 있습니다. 

## 기술 스택
### 백엔드
- Spring boot
- Spring Security
- Redis
- Socket io

### 프론트엔드
- React
- Next js
- TypeScript
- Socket io

## 프로젝트 구조
<p align="center">
  <img src="https://github.com/kitewater/teambeam-backend/assets/97283971/16aede00-6a1a-4bb4-8554-11c672634790" width="100%">
</p>

# 기능
## 메인페이지
### 1. 소셜 로그인 기능
https://github.com/kitewater/teambeam-backend/assets/97283971/a0fc1e5b-a0eb-41ea-a379-ab92f547f75b
- 카카오 소셜 로그인 기능
- 이메일 가입은 인증코드를 통한 가입
- JWT 사용

### 2. 프로젝트 생성 & 참여
https://github.com/kitewater/teambeam-backend/assets/97283971/b825a02f-70d6-4d04-bd12-8395fb8035ca
- 프로젝트 생성 가능
- 프로젝트에 초대 코드를 받으면 참여 가능

## 팀페이지
### 1. 투두리스트 만들기
https://github.com/kitewater/teambeam-backend/assets/97283971/b9af08f4-0059-427d-83e5-aba8e4f856ec
- 투두리스트 만들기 가능
- 투두리스트는 상위, 중위, 하위로 구성됨

### 2. 캘린더 기능
https://github.com/kitewater/teambeam-backend/assets/97283971/ed40118a-077d-4739-88fe-9cb1f48166b4
- 스케줄 생성 가능
- 캘린더에는 상위 투두의 일정들과 스케줄들이 표시됨

### 3. 채팅 기능
https://github.com/kitewater/teambeam-backend/assets/97283971/92f4b182-8022-4443-acd0-b8edde35d3a8
- 채팅 페이지에서 채팅 가능
- 특정 채팅에 답글을 달 수도 있음

### 4. 게시물 업로드 기능
https://github.com/kitewater/teambeam-backend/assets/97283971/0c882b13-0c22-4328-af00-3c57f2a1b8f7
- 게시물은 표, 게시물 두 형태로 업로드 가능
- 게시물에 댓글 달 수 있음
- 게시물을 북마크 할 수도 있음

## 개인페이지
### 1. 개인페이지
https://github.com/kitewater/teambeam-backend/assets/97283971/c53fa673-d4d4-4e25-888a-7432aa318193
- 내가 속한 프로젝트들에서 투두리스트와 스케줄을 가져와서 렌더링 해줌

### 2. 메모 기능
https://github.com/kitewater/teambeam-backend/assets/97283971/4e538015-692e-440b-bb5d-dbba915e2111
- 개인적인 메모를 할 수 있음

### 3. 북마크 기능
https://github.com/kitewater/teambeam-backend/assets/97283971/a119929a-06e8-4663-a7a5-afdc454cccfb
- 내가 다른 프로젝트에서 북마크한 게시물들을 보여줌
