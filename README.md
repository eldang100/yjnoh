# 방문간호 일정관리 PWA

GitHub Pages에 그대로 업로드해서 사용하는 버전입니다.

- 기존 일정 LocalStorage 유지
- 잘못된/구버전 일정 데이터가 있어도 달력 렌더링이 멈추지 않도록 자동 정규화
- JSON 일정 백업/복원
- Service Worker 캐시 버전 자동 교체
- HTML은 네트워크 최신 버전을 우선 확인

## GitHub 업데이트
기존 저장소의 `index.html`, `sw.js`, `manifest.webmanifest`, `icons`를 이 폴더의 파일로 교체하세요.
기존 사용자는 앱/사이트 데이터를 삭제하지 않는 한 저장된 일정이 유지됩니다.
