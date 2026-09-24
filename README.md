# 방문간호 일정관리

GitHub Pages에 올리면 iPhone/Android에서 홈 화면 앱처럼 사용할 수 있는 PWA입니다.

## GitHub Pages
1. 이 폴더의 파일을 GitHub 저장소 루트에 업로드합니다.
2. GitHub → Settings → Pages → Deploy from a branch → main / root 선택.
3. 생성된 `https://사용자.github.io/저장소명/` 주소를 휴대폰에서 엽니다.

## iPhone
Safari에서 주소를 연 뒤 `공유` → `홈 화면에 추가`를 선택합니다.
앱 아이콘은 `icons/icon-180.png`가 사용됩니다.

## Android
브라우저가 설치 가능한 상태를 감지하면 화면 오른쪽 아래의 `홈 화면에 추가` 버튼을 눌러 설치할 수 있습니다.

## 포함된 기능
- 방문간호 일정관리 원본 기능 유지
- PWA manifest
- 홈 화면 아이콘
- iPhone용 apple-touch-icon
- Android/Chrome 설치 프롬프트
- iPhone용 홈 화면 추가 안내
- 기본 오프라인 캐시(service worker)
