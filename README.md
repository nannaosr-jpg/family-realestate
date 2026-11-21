# 가족 부동산 지도

가족 전용 부동산 지도입니다. 개인정보 보호를 위해 **모든 자산 데이터는 AES-256-GCM 으로 암호화**되어 있으며,
비밀번호를 입력해야 열립니다. (PBKDF2-HMAC-SHA256 키 유도 + Web Crypto API 복호화, 단일 HTML 파일)

- 접속 주소: https://nannaosr-jpg.github.io/family-realestate/
- 홈 화면에 설치(PWA)할 수 있습니다: Android 크롬은 주소창 메뉴 → "앱 설치",
  iPhone 사파리는 공유 → "홈 화면에 추가".
- 이 저장소에는 암호화된 `index.html` 과 앱 설정 파일(`manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`)만
  들어 있습니다. 원본 데이터·엑셀·스크립트는 없습니다.
