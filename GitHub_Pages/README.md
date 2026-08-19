# 상남동 좋은데이 맛집 MAP

GitHub Pages 배포용 버전입니다.

## 현재 포함 기능

- 상단 좋은데이 포스터
- 이벤트 참여 안내 이미지
- 전체 업소 목록
- 검색 / 카테고리
- GOODDAY PICK 랜덤 추천
- 2차 장소 추천
- 직감 상세보기
- 뽀뽀쪽갈비 상세보기
- 네이버지도 / 카카오맵 / 설치 지도앱 선택
- 지도 앱 실행 취소 후 선택창 자동 복구
- GA4 방문/지도 클릭 추적

## GitHub Pages 업로드

1. GitHub에서 새 Repository를 생성합니다.
2. 이 ZIP을 PC에서 압축 해제합니다.
3. 압축을 푼 폴더 안의 **파일과 폴더 전체**를 Repository 최상위에 업로드합니다.
   - index.html
   - images/
   - .nojekyll
   - 404.html
   - 기타 README 파일
4. Repository → Settings → Pages
5. Build and deployment → Source → `Deploy from a branch`
6. Branch → `main`
7. Folder → `/(root)`
8. Save

보통 사이트 주소:
`https://GitHub아이디.github.io/저장소명/`

## 이미지 추가 방법

예:
- `images/bbo_interior.jpeg`
- `images/bbo_menu.jpeg`

업소 상세보기 HTML에서 지정된 이름과 동일한 사진을 `images` 폴더에 넣으면 표시됩니다.

## 중요

이 버전은 GitHub Pages의 프로젝트 주소가 `/저장소명/` 아래에 생성되는 경우에도
사진이 보이도록 `/images/...`가 아닌 `./images/...` 상대경로를 사용합니다.
