# GitHub Pages 이력서 템플릿

`index.html` 하나로 동작하는 단일 페이지 이력서 템플릿입니다.

## 공개 URL (확정)

현재 저장소 이름이 `page`라면 GitHub Pages 공개 주소는 아래처럼 확정됩니다.

- **프로젝트 페이지(권장):** `https://<username>.github.io/page/`

> 예: GitHub 아이디가 `violetbeach`라면 `https://violetbeach.github.io/page/`

루트 주소(`https://<username>.github.io/`)로 바로 접속되게 하려면 저장소 이름을 `<username>.github.io`로 만들어야 합니다.

## 사용 방법

1. `index.html`에서 이름, 연락처, 경력/프로젝트 내용을 본인 정보로 수정합니다.
2. 저장소 Settings > Pages에서 배포 브랜치를 `main` / `/ (root)`로 지정합니다.
3. `main` 브랜치에 푸시하면 GitHub Pages에 자동 반영됩니다.

## 커스터마이징 팁

- 컬러 테마: `:root` CSS 변수 수정
- 섹션 추가: `main` 내부에 `<section class="section">...</section>` 블록 복사
- 기술 스택 태그: `Skills` 섹션의 `<span>` 항목 편집


## 새로 추가된 기능

- 상단 버튼으로 **라이트/다크 테마 전환** 가능 (선택값은 브라우저에 저장)
- 프로필 사진 표시 지원 (`index.html`의 `img.profile-photo` `src`를 본인 이미지로 변경)
