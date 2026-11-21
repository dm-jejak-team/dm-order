# 디자인 제작물 접수 페이지

DM기획 디자인 제작물 접수·시안 피드백 웹페이지입니다. GitHub Pages로 열리고, 접수 데이터는 구글 Apps Script 웹앱(구글 시트 + 비공개 구글 드라이브 폴더)에 저장됩니다.

- 사이트: https://dm-jejak-team.github.io/dm-order/
- 화면 파일: `index.html` 하나에 전체 화면이 들어 있습니다.
- 백엔드: 구글 Apps Script 웹앱 (POST로 JSON 요청·응답)

## 수정 방법

1. `index.html`을 고쳐 `main` 브랜치에 커밋하면 1~2분 안에 사이트에 반영됩니다.
2. 백엔드(Apps Script) 코드는 Apps Script 편집기에서 고친 뒤 **배포 관리 → 수정 → 새 버전**으로 다시 배포해야 반영됩니다.
