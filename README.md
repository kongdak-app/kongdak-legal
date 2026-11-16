# site/legal

Kongdak의 공개 약관 · 개인정보 처리방침 · 지원 페이지예요. 이 폴더가 나중에 공개 저장소의 루트가 돼요.

## 직접 고치지 마세요

이 폴더의 파일은 이 README까지 모두 만들어진 결과물이에요.

- 약관 · 처리방침 글: `docs/legal/*.md` 를 고쳐요. 영어와 한국어를 같은 내용으로 맞춰요.
- 첫 페이지 · 지원 페이지의 글과 모양: `tools/legal/build_site.py` 안에 있어요.
- 고친 뒤 `python3 tools/legal/build_site.py` 로 다시 만들어요.
- `python3 tools/legal/build_site.py --check` 는 최신인지 확인해요. 다르면 파일 이름을 알려 주고 1로 끝나요.

## 공개

- 저장소: `kongdak-app/kongdak-legal` (공개 저장소 + GitHub Pages). 2026-11-16 사장님 OK로 공개했어요.
- 고친 뒤에는 다시 만든 이 폴더를 그 저장소에 그대로 올려요(내용을 바꾸는 공개는 사장님 OK 뒤에).
- 페이지에는 스크립트, 바깥 글꼴 · 그림, 분석 도구가 없어요. 페이지끼리는 상대 주소로만 이어져요.

## 주소 8개

- https://kongdak-app.github.io/kongdak-legal/ : 영어 첫 페이지
- https://kongdak-app.github.io/kongdak-legal/terms.html : Terms of Use
- https://kongdak-app.github.io/kongdak-legal/privacy.html : Privacy Policy
- https://kongdak-app.github.io/kongdak-legal/support.html : Support
- https://kongdak-app.github.io/kongdak-legal/ko/ : 한국어 첫 페이지
- https://kongdak-app.github.io/kongdak-legal/ko/terms.html : 이용약관
- https://kongdak-app.github.io/kongdak-legal/ko/privacy.html : 개인정보 처리방침
- https://kongdak-app.github.io/kongdak-legal/ko/support.html : 지원
