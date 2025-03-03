# WB38_Project_UI

## 개요
WB38_Project_UI는 다음과 같은 기능을 제공합니다:

- **Mainpage**: GIF를 이용한 메인 페이지와 로그인, 회원 가입 창 구현
- **Dashboard**: `useState`를 이용해 5단계의 화면 전환 구현
- **Chat**: FAQ 클릭 기능 구현 (DB와 Rasa 연동)
- **History**: 서버로부터 받은 정보를 카드 형태로 구현
- **Login**: 세션 스토리지를 통해 현재 로그인 상태 구현 및 계정 DB 연동

## 시작 방법
1. 필요한 모듈을 설치합니다.
2. Terminal에서 다음 명령어를 실행합니다:
   ```bash
   npm start
   ```
3. `src/routes/sections.jsx`에서:
   - 21: 메인 화면부터 실행 (서버 필요 O)
   - 22: 대시보드부터 실행 (서버 필요 X)

## 참고 사이트
This is the [source](https://mui.com/store/items/minimal-dashboard-free/).
