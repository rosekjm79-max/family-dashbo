# Family Dashboard

가족용 생활 대시보드 — 단일 HTML 파일로 동작하는 개인 페이지입니다.

## 구성

- `index.html` — 앱 전체 (HTML + CSS + JavaScript 한 파일, 외부 빌드 없음)
- 4자리 PIN 잠금 화면 (해제 상태는 기기 브라우저에 저장)
- Firebase Realtime Database로 기기 간 실시간 동기화
- PWA 메타 태그 + 인라인 아이콘: 휴대폰 홈 화면에 추가하면 앱처럼 열립니다

## 사용

GitHub Pages 주소를 열고 4자리 PIN을 입력합니다.
휴대폰 브라우저 메뉴에서 "홈 화면에 추가"를 선택하면 아이콘이 생깁니다.

개인용 페이지로, 검색 엔진 노출을 막기 위해 `noindex`로 설정되어 있습니다.
