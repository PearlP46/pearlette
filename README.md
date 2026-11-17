# pearlette ♡ — GitHub Pages + Pages CMS

로제트와 펄을 위한 로맨틱 개인 갤러리와 기록 아카이브.

## 사이트를 처음 공개하기

1. GitHub에서 **Public** 저장소 `pearlette`를 만든다. (계정: `pap891974-dot`)
2. 이 ZIP을 풀고 **안에 있는 파일·폴더 전체를** 저장소 최상위에 업로드한다. (ZIP 자체를 업로드하면 안 됨!) `Add file → Upload files`에서 드래그 앤 드롭.
3. `Settings → Pages → Build and deployment`에서 `Source: Deploy from a branch`, `Branch: main`, 폴더 `/(root)`를 선택하고 `Save`.
4. 공개 주소: `https://pap891974-dot.github.io/pearlette/` (실제로 공개한 뒤에 접속 가능).

## 코딩 없이 새 글 / 새 그림을 올리려면

1. https://app.pagescms.org/ 에서 **GitHub 계정으로 로그인**하고 Pages CMS GitHub 앱 연결을 승인한다.
2. 저장소 `pap891974-dot/pearlette`를 선택한다.
3. 왼쪽의 **일기 · Journal** → 새 글에서 제목, 날짜, 본문을 작성한 후 저장한다.
4. **그림 · Gallery** → 새 작품에서 제목과 이미지 파일을 선택해 저장한다.
5. **사이트 소개 · About**에서 메인 이미지·소개 글을 교체할 수 있다.
6. 수정 사항이 GitHub에 저장되면 GitHub Pages가 사이트를 다시 빌드해 반영한다.

## 중요한 참고

- 기존 이미지 11장을 `media/`에 저장해 두었다. 작품 제목은 임시 이름 `Artwork 01`처럼 지정했다. 수정하거나 삭제해도 된다.
- 게시글 1개는 사용법 확인을 위한 임시 글이다.
- GitHub Pages 무료 공개 사이트의 **저장소는 Public**으로 운영하는 것이 기본이다. 비공개 일기·개인정보를 올리지 말 것.
- 사이트가 보여주는 내용은 공개되며, 편집은 GitHub 권한이 있는 사용자만 할 수 있다.
- 댓글, 방명록, 로그인, 좋아요 기능은 만들지 않았다.
- **저장소 이름을 다르게 만들면** `_config.yml`의 `baseurl`과 `url`을 수정해야 한다.
- 날짜는 Pages CMS에서 수정하고, 게시글/작품 페이지가 자동 생성된다.
- 개인 도메인을 구매할 필요가 없다.
