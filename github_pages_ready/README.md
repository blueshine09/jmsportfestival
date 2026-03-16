# GitHub Pages 업로드용 파일

이 폴더는 GitHub Pages에 바로 올릴 수 있도록 정리된 버전입니다.

## 포함 파일
- `index.html` : 메인 페이지
- `.nojekyll` : GitHub Pages 정적 배포 안정화용

## 사용 방법
1. GitHub 저장소를 연다.
2. `Add file` → `Upload files`
3. 이 폴더 안의 파일들을 업로드한다.
4. 저장소 `Settings` → `Pages`
5. `Build and deployment`에서
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
6. 저장 후 잠시 기다리면 사이트가 열린다.

## 주의
이 페이지는 HTML 내부에서 Google Apps Script 주소로 데이터를 불러오는 구조입니다.
따라서 Apps Script 배포가 공개 접근 가능 상태여야 GitHub Pages에서도 정상 동작합니다.
