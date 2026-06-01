# 「모두의 아이디어」 아이디어 고도화(정책 분야) 가이드북 — HTML 페이지

> 정책 분야 가이드북 원본(`(정책)..._260601.docx`)을 100% 충실 변환한 MD를 단일 HTML로 구조화한 웹 가이드북.
> 기술판 `guidebook/`과 동일 디자인, 내용만 정책 분야.

## 구성

```
guidebook-policy/
├── index.html        ← 가이드북 본문 (앱셸 + 좌측 목차 + 내부 스크롤)
├── logo-white.png    ← 흰색 녹아웃 로고
├── vercel.json       ← 보안 헤더 + cleanUrls (정적, functions 없음)
├── .gitignore
└── README.md
```

## 배포 정보

- GitHub: `hbb302/moduidea-guidebook-policy`
- **Vercel: https://moduidea-policy-guidebook.vercel.app** (고정 배포 URL)
- 챗봇(정책) 연동: https://moabot-policy.vercel.app

## 주요 특징

- **원본 100% 충실 반영**: 핵심 요약 + Ⅰ~Ⅷ장 + [참고], FAQ 22문항, 표 14개
- 좌측 사이드바 목차(章+절) + 스무스 스크롤 + 스크롤스파이 + 모바일 햄버거
- 앱셸 내부 스크롤 구조, 브랜드 디자인(보라 그라데이션, Pretendard)
- 헤더 "모아봇에게 질문" → 정책 챗봇

## 콘텐츠 갱신 방법

1. 정책 가이드북 docx 갱신본 수령.
2. `_policy_work/convert_policy.py`로 충실 MD 재생성 → `_policy_work/verify_fidelity.py` 검증.
3. `_policy_work/generate_page.py`로 페이지 재생성 → `_policy_work/verify_page.py` 검증.
4. `git push` → Vercel 자동 재배포 (URL 유지).

## ⚠️ 원본 목차↔본문 불일치 (다른 팀 확인 필요)

원본 docx의 **앞 목차**와 **본문 章 제목**이 일부 다릅니다 (본 페이지는 "본문 기준"으로 작성):

| 章 | 목차 표기 | 본문 실제 제목(페이지 반영) |
|---|---|---|
| Ⅰ | 사업 개요 | 아이디어 고도화 프로그램 |
| Ⅱ | 멘토링 프로그램 개요 | 아이디어 고도화 멘토링 |
| Ⅵ | (절 3개) | "4. 비용 부담 안내" 추가됨 |

상세는 `_policy_work/원본_불일치_메모.txt` 참조.

## 문의

정책 분야 수행기관 ㈜엠와이소셜컴퍼니 · 02-499-5111 · idea2policy@gmail.com
