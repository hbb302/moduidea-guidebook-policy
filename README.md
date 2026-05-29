# 「모두의 아이디어」 아이디어 고도화(정책 분야) 가이드북 — 준비 중 페이지

> **현재 상태: 콘텐츠 준비 전 임시(Coming Soon) 페이지입니다.**
> 정책 분야 매뉴얼 미수령 상태에서, 다른 팀 배포용 링크를 먼저 확보하기 위해 만든 플레이스홀더입니다.
> 가이드북 내용이 확정되면 본 페이지를 실제 콘텐츠로 교체합니다.

## 구성

```
guidebook-policy/
├── index.html        ← '준비 중' 안내 페이지 (기술판 guidebook과 동일 브랜드 디자인)
├── logo-white.png    ← 흰색 녹아웃 로고
├── vercel.json       ← 보안 헤더 + cleanUrls
├── .gitignore
└── README.md
```

## 배포 정보

- GitHub: `hbb302/moduidea-guidebook-policy`
- Vercel: https://moduidea-policy-guidebook.vercel.app
- 챗봇(정책) 연동 버튼: https://moabot-policy.vercel.app

## 기술판과의 관계

| 분야 | 가이드북 | 챗봇 |
|---|---|---|
| 기술 | https://moduidea-guidebook.vercel.app (콘텐츠 완성) | https://moabot.vercel.app (콘텐츠 완성) |
| 정책 | **본 페이지 (준비 중)** | https://moabot-policy.vercel.app (준비 중) |

## 콘텐츠 채우는 방법 (추후)

1. 정책 분야 가이드북(매뉴얼) 확정본 수령.
2. 기술판 `guidebook/index.html` 구조(앱셸 + 좌측 목차 사이드바 + 본문)를 토대로 정책 분야 내용으로 작성.
   - 정책 분야는 챕터·소절 구성이 기술판과 다를 수 있으므로 목차부터 재구성.
3. 본 `index.html`을 실제 가이드북으로 교체 후 `git push` → Vercel 자동 재배포.
   - **URL은 그대로 유지**되므로 이미 배포한 링크를 다시 보낼 필요 없음.

## 문의

프로그램 담당: 02-6338-1726 · rnbdp@rnbdp.com
