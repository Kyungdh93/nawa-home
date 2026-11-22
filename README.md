# NAWA 홈 (nawa.io.kr)

NAWA가 운영하는 서비스(라클, 게임들)로 연결하는 대표 페이지. GitHub Pages로 배포한다.

- 주소: https://nawa.io.kr (가비아 DNS A 레코드 → GitHub Pages)
- 빌드 도구 없음. `index.html`, `privacy.html`, `assets/`만 수정한다.
- `ads.txt`: Google AdSense 게시자 인증 파일. 하위 도메인(게임) 광고에도 적용되므로 지우지 않는다.

## 서비스 추가

새 게임을 `<이름>.nawa.io.kr`로 열면:
1. `index.html`의 서비스 카드에 하나 추가 (스크린샷·아이콘은 `assets/img/`)
2. `privacy.html`의 "운영하는 다른 서비스" 목록에 추가
3. 푸터 링크에 추가

## 관련 저장소

- 라클 소개 페이지: `nawa-pages` → https://lacle.nawa.io.kr
- 투회말 구아웃: `robot-baseball` → https://nineouts.nawa.io.kr (Cloudflare Pages)
