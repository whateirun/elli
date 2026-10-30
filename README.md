# 표지판 원근 글씨 합성기

## GitHub Pages 배포
1. GitHub에서 저장소를 만듭니다.
2. 이 ZIP의 최상위 폴더 안에 있는 **모든 항목**을 저장소 최상위(root)에 업로드합니다. `index.html`과 `assets` 폴더가 같은 단계에 있어야 합니다.
3. `assets` 폴더 안에는 `sign-base.png`, `site-logo.png`, `dobong.ttf`가 모두 있어야 합니다.
4. 저장소의 **Settings → Pages**로 이동합니다.
5. **Deploy from a branch**를 선택하고 배포 브랜치(예: `main`)와 폴더 `/(root)`를 지정한 뒤 Save를 누릅니다.
6. 배포가 완료되면 표시되는 GitHub Pages 주소로 접속합니다.

## 저장 위치 지정
- 최신 Chrome 또는 Edge에서 HTTPS로 제공되는 GitHub Pages 사이트에 접속하면 `다른 이름으로 저장` 버튼을 눌러 PC의 저장 위치와 파일명을 직접 지정할 수 있습니다. 같은 이름의 파일이 있으면 브라우저가 덮어쓰기 확인을 표시할 수 있습니다.
- 브라우저 보안 정책상 폴더 접근 권한은 브라우저가 관리합니다. 폴더 직접 지정 기능을 지원하지 않는 브라우저에서는 `다른 이름으로 저장` 버튼으로 대체되어 브라우저의 저장 기능을 사용합니다.
- 로컬 파일(`file://`)로 직접 열기보다 GitHub Pages HTTPS 주소에서 사용하는 것을 권장합니다.

## 기능
- 네 모서리 좌표를 브라우저 localStorage에 자동 저장합니다.
- 같은 브라우저와 같은 GitHub Pages 주소에서는 다음 접속에도 설정이 유지됩니다.
- 미리보기와 저장 결과는 1080 × 1080 PNG입니다.
- 기본 배경 `sign-base.png`를 사용하거나 화면의 배경 이미지 파일 추가 기능으로 다른 이미지를 사용할 수 있습니다.
- PNG 다운로드 시 조절점은 제외됩니다.

## 참고
브라우저 저장 방식이므로 다른 PC·브라우저·시크릿 창에는 모서리 설정이 자동으로 동기화되지 않습니다.

## 포함 글꼴
- 도봉옛길체 (Medium)
- 나눔명조 (Regular, Bold, ExtraBold)
- Black Han Sans (Regular)
- Noto Sans KR (Thin–Black, variable weight)
- Aiharakantei_200
- Otsutome_font_ver3_20
- しょかきうたげ_無料版_


글꼴 파일은 `assets/` 내부에 포함되어 있어 GitHub Pages에서 별도 외부 폰트 서버 없이 로드됩니다. 각 글꼴의 라이선스 파일은 `assets/fonts/`에 함께 포함되어 있습니다. 추가 글꼴은 `assets/fonts/added/`에 포함되어 있으며, 글꼴 이름이 깨져 보일 수 있는 파일은 상위 폴더 이름을 선택 목록에 사용합니다. 각 글꼴에 동봉된 라이선스/안내 파일도 같은 폴더에 포함했습니다.
