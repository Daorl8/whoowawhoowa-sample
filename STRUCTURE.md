# STRUCTURE · whoowa-sample

```
whoowa-sample/
├─ index.html              단일 파일 (CSS·JS 인라인)
├─ wrangler.toml           name = whoowa-sample → whoowa-sample.lgt3232.workers.dev
├─ .assetsignore           img/ · 문서 · index_*.html · _deploy 배포 제외
├─ wh-dohyeon.woff2        제목 · 라벨 (Do Hyeon)
├─ wh-himelody.woff2       손글씨 쪽지 (Hi Melody)
├─ wh-pretendard.woff2     본문 (Pretendard 400–700)
├─ wh-cat.webp             고양이 캐릭터 투명 (히어로 · 칵테일)
├─ wh-cat-face.webp        고양이 얼굴 (헤더 · 푸터) · favicon.png
├─ wh-door.webp            히어로 민트 문 + 손글씨 쪽지
├─ wh-cf-*.webp            COFFEE SIDE 4장
├─ wh-ck-1~4.webp          COCKTAIL SIDE 4장
├─ wh-front / wh-room / wh-sofa / wh-bar .webp   SPACE
├─ og-whoowa.jpg
├─ img/                    다올 제공 원본 40장 (배포 제외 · 사람 · 타 브랜드 · 그림책 표지 포함, 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로(크림) → `.fork` 갈림길(민트 | 남색) → `#coffee`(크림) → `#cocktail`(남색) → THE NAME(크림) → `#space`(고양이 노랑) → `#visit`(크림) → 푸터(남색) + 모바일 `.quick`.

## 지점 정보 교체 (둔산점 확정 시)
주소 3곳(Visit · 푸터 · JSON-LD) · 영업시간 4곳(히어로 `.when` · Visit · 푸터 · JSON-LD) · 전화(`tel:` 전부 + 표시 + JSON-LD) · 네이버 place id 2곳(Visit 버튼 · `.quick`) · 구글 지도 `q=` · 메타 description.

## 폰트 재생성
문구를 바꾸면 빠진 글자 검사(LESSONS §26) · `--name-IDs='*' --name-languages='*' --name-legacy`(§24).
