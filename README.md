# 팀글벙글
프로젝트 일정 관리 서비스

## 기술 스택
### 백엔드
Spring boot, Spring Security, Redis, Socket io
### 프론트엔드
React, Next js, TypeScript, Socket io

## 기능
1. 소셜 로그인 기능
   - 카카오 소셜 로그인 기능
   - 이메일 가입은 인증코드를 통한 가입
   - JWT 사용
     
2. 프로젝트 생성 & 참여
   - 프로젝트 생성 가능
   - 프로젝트에 초대 코드를 받으면 참여 가능
     
3. 투두리스트 만들기
   - 투 두 리스트 만들기 가능
   - 투 두 리스트는 상위, 중위, 하위로 구성됨
4. 캘린더 기능
   - 스케쥴 생성가능
   - 캘린더에는 상위 투두의 일정들과 스케쥴들이 표시됨
5. 채팅 기능
   - 채팅 페이지에서 채팅 가능
   - 특정 채팅에 답글을 달 수도 있음
6. 게시물 업로드 기능
   - 게시물은 표, 게시물 두 형태로 업로드 가능
   - 게시물에 댓글 달 수 있음
   - 게시물을 북마크 할 수도 있음
6. 개인 페이지 기능
   - 개인페이지에는 내가 속한 프로젝트들에서 투 두 리스트와 스케쥴을 가져와서 렌더링 해줌
   - 개인적인 메모를 할 수 있음
   - 내가 다른 프로젝트에서 북마크 한 게시물들을 보여줌  
## 프로젝트 구조
  <p align="center">
    <img src="https://github.com/kitewater/teambeam-backend/assets/97283971/16aede00-6a1a-4bb4-8554-11c672634790" width="100%">
  </p>

## 배포 구조
  <p align="center">
    <img src="https://github.com/kitewater/teambeam-backend/assets/97283971/5c5bde10-a062-4f4f-a626-9d9ea8e6b240" width="50%" height="500">
  </p>
