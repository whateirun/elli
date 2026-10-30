# 표지판 원근 글씨 합성기

## 로컬에서 실행
`index.html`을 브라우저에서 열거나, 폴더에서 간단한 로컬 웹 서버를 실행하세요.

## GitHub Pages 배포
1. GitHub에서 새 Public 또는 Private 저장소를 만듭니다.
2. 이 폴더 안의 `index.html`과 `assets/sign-base.png`를 저장소 최상위에 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Deploy from a branch**를 선택하고 `main` / `/(root)`를 지정한 뒤 Save를 누릅니다.
5. 잠시 후 표시되는 Pages 주소로 접속합니다.

## 기능
- 네 모서리 좌표를 브라우저 localStorage에 자동 저장합니다.
- 같은 브라우저와 같은 GitHub Pages 주소에서는 다음 접속에도 설정이 유지됩니다.
- 문장 길이에 맞춰 글자 크기를 자동 조절하며, 짧은 문장은 표지판을 가득 채우지 않습니다.
- PNG 다운로드 시 조절점은 제외됩니다.

## 참고
브라우저 저장 방식이므로 다른 PC·브라우저·시크릿 창에는 설정이 자동으로 동기화되지 않습니다.

