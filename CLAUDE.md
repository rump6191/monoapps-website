# MonoApps Website 개발 가이드

## 다국어 지원

이 웹사이트는 5개 언어를 지원합니다:
- 한국어 (기본): `/` (루트)
- English: `/en/`
- 日本語: `/ja/`
- 中文: `/zh/`
- Español: `/es/`

### 중요: 콘텐츠 수정 시 다국어 확인 필수

**HTML 파일 수정 시 반드시 다른 언어 버전도 함께 수정해야 합니다.**

수정이 필요한 파일들:
- `index.html` → `en/index.html`, `ja/index.html`, `zh/index.html`, `es/index.html`
- `support.html` → `en/support.html`, `ja/support.html`, `zh/support.html`, `es/support.html`
- `news.html` → `en/news.html`, `ja/news.html`, `zh/news.html`, `es/news.html`
- `privacy.html` → `en/privacy.html`, `ja/privacy.html`, `zh/privacy.html`, `es/privacy.html`
- `terms.html` → `en/terms.html`, `ja/terms.html`, `zh/terms.html`, `es/terms.html`

### 체크리스트

- [ ] 한국어 페이지 수정
- [ ] 영어 버전 수정
- [ ] 일본어 버전 수정
- [ ] 중국어 버전 수정
- [ ] 스페인어 버전 수정
