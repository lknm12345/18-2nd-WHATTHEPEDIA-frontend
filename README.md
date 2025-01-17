# 🎞 WHAT THE PEDIA

**React로 구현한 맞춤형 영화 추천 및 평가 서비스**

> ## ✨ 프로젝트 소개
>
> 왓챠피디아를 모티프로 한 맞춤형 영화 추천 및 평가 서비스

- **프로젝트 기간**
  📆 2021.03.29 ~ 2021.04.09

- **팀원**
  
  🎞 Front-end : 강준우, 김우영, 남궁선아
  
  🎞 Back-end : 예병수, 최인아

> ## ✨ 구현 사항

### 💎 메인 페이지

- 네비게이션 바
  - 로그인 여부에 따라 상태 변화
  - Location을 통해 현재 페이지를 인식하여 스크롤 이벤트 상태 변화
- 영화 리스트 슬라이드 기능(캐로셀)
  - 받는 데이터 양의 따른 캐로셀 구현

### 💎 로그인/회원가입 모달창

-  자체 로그인/회원가입
    - 컴포넌트, 함수 재사용을 통한 모달창 구현
    - 정규식을 활용한 로그인/회원가입 유효성 체크
    - 로그인/회원가입 `input값` 유효성 체크 통과 여부 실시간 알림 기능
- 카카오 소셜로그인
  - OAuth2.0 기반 카카오 로그인 API 연동
- 로그아웃

### 💎 영화 상세 페이지

- 영화별 별점 기능
  - 별(svg)값을 Boolean을 활용하여 별점 구현
  - POST방식을 활용하여 별점 데이터 전송
- 그래프 기능
  - 전체 사용자 별점 통계 기능
  - chart라이브러리를 활용하여 영화별 데이터를 받음
  - 객체 데이터를 배열 형식으로 변경하여 접목
- 갤러리 및 코멘트
  - JavaScript를 이용하여 캐러셀 기능 직접 구현
  - `params`로 동적라우팅을 활용한 페이지 이동 구현

### 💎 마이페이지
- 사용자 정보 API 연동

### 💎 마이페이지 영화 상세페이지
  - 별점순/가나다순/개봉일순 정렬 기능
  - 토큰으로 해당 유저 데이터 받아오기
  - 정렬 필터 모달창 구현

> ## ✨ 기술 스택

- React / React Hooks
- JavaScript(ES6+)
- Styled Components
- HTML,CSS
