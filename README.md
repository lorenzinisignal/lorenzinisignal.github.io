# Today I Learned

매일 배운 것을 기록하는 블로그입니다: <https://lorenzinisignal.github.io>

[Jekyll](https://jekyllrb.com/)과 [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) 테마로 만들었고, `main` 브랜치에 push하면 GitHub Actions가 자동으로 빌드하고 배포합니다.

## 글 작성

`_posts/YYYY-MM-DD-영문-slug.md` 파일을 만들고 맨 위에 front matter를 적습니다.

```yaml
---
title: "글 제목"
date: 2026-11-14 09:00:00 +0900
categories: [Dev, Frontend]   # [대분류, 소분류]
tags: [javascript, react]     # 태그는 소문자 권장
---
```

## 카테고리 규칙

대분류는 아래 4개 중 하나만 씁니다. 소분류는 자유롭게 추가해도 되지만, 이미 있는 이름을 다시 쓰는 것을 우선합니다.

| 대분류 | 다루는 내용 | 소분류 예시 |
|---|---|---|
| `Dev` | 개발, 프로그래밍 | `Frontend`, `Backend`, `DevOps`, `AI`, `Tools` |
| `Design` | 디자인, UI/UX | `UI/UX`, `Figma`, `Typography`, `Inspiration` |
| `Investment` | 투자, 경제 공부 | `Stocks`, `ETF`, `Crypto`, `Economy` |
| `ETC` | 그 밖의 모든 것 | `Blog`, `Life`, `Books`, `Review` |

- 카테고리 이름은 대소문자를 구분합니다. `Dev`와 `dev`는 서로 다른 카테고리가 됩니다.
- 카테고리는 글이 하나 이상 있을 때만 카테고리 페이지에 나타납니다.

## 로컬 실행

```bash
bundle install
bundle exec jekyll serve   # http://127.0.0.1:4000
```
