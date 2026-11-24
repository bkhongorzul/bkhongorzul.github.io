# bkhongorzul.github.io

Khongorzul Battumur(바트투무르 헌거르졸)의 개인 포트폴리오 사이트입니다.

- 사이트: <https://bkhongorzul.github.io/> (기본 영어, 한국어로 바로 열기: <https://bkhongorzul.github.io/?lang=ko>)
- 이력서: [국문 PDF](resume-ko.pdf) · [English PDF](resume-en.pdf)

## 주요 기능

- 한국어/영어 전환 (KO / EN)
- 라이트/다크 모드
- 학력, 경력, 프로젝트, 기술 소개
- 프로젝트별 "자세히 보기"로 문제 정의, 작동 방식, 구현 내용, 사용 기술 확인
- 국문·영문 이력서 PDF 다운로드

## 구성

| 파일 | 설명 |
| --- | --- |
| `index.html` | 포트폴리오 페이지 (HTML, CSS, JavaScript 한 파일, 빌드 과정 없음) |
| `resume-ko.pdf` | 국문 이력서 (A4 1쪽) |
| `resume-en.pdf` | 영문 이력서 (A4 1쪽) |

글꼴은 Google Fonts(Google Sans Flex, Roboto Mono)와 Pretendard를 CDN으로 불러옵니다. 그 외 외부 라이브러리는 사용하지 않습니다.

## 로컬에서 확인하기

빌드 과정이 없는 정적 페이지이므로 `index.html`을 브라우저로 열면 됩니다.

```bash
python3 -m http.server 8000
# http://localhost:8000 접속
```

## 배포

`main` 브랜치에 푸시하면 GitHub Pages(Settings → Pages → Deploy from a branch, `main` / `(root)`)가 자동으로 배포합니다.

## 연락처

- Email: khongorzul.batt@gmail.com
- GitHub: [@bkhongorzul](https://github.com/bkhongorzul)
