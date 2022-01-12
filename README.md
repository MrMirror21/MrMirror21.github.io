# Walkle 개발 경과 공유용 배포

## 1. https://mrmirror21.github.io/ 로 접속

## 2. 현재 진행상황
https://www.notion.so/19c8b4f0f04349a48fb1791debc71dea

- 서버와의 연결 x, recoil 라이브러리를 통해 가짜 데이터(크리에이터, 프로젝트)들을 서버에 있는 것처럼 흉내.
- 현재 배포 버전 상으로 walklemap 페이지 오류로 인해 확인 불가능

### 확인 가능한 페이지 목록
- 랜딩 페이지 (검색 시 walklemap 페이지로 이동하나, 이후 기능 정지하므로 다시 랜딩페이지로 돌아가야함)
- 로그인, 회원가입 페이지
- 프로필 등록 페이지
- 프로젝트 페이지
- 프로젝트 등록 페이지
- 프로젝트별 상세 페이지
  - 본래 로그인을 통한 사용자 확인으로 관리자/사용자 뷰가 나뉘어야 하나 관리자모드/사용자모드 버튼으로 대체 
- 프로젝트 수정 페이지

## 3. 주의사항
- github page 라우팅 특성상 랜딩페이지(github.io/ 상태) 외의 페이지에서 새로고침을 할 경우 404 오류 발생

기타 문의사항은 슬랙, 카톡, 연락 가능한 모든 수단으로 프론트 개발자에게
