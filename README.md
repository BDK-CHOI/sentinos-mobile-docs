# Sentinos Mobile Docs Site

기획·디자인 문서를 브라우저에서 보기 위한 **정적 사이트**입니다.

## 생성

```bash
npm install
npm run docs:build
```

소스는 Markdown 정본입니다.

- `docs/product/sentinos-mobile-기획-v2.2.md`
- `docs/design/sentinos-mobile-디자인-컨셉.md`

수정 후 `npm run docs:build`를 다시 실행하세요.

## 로컬 / 사내 공유

```bash
npm run docs:serve
```

- 본인 PC: http://localhost:4173  
- 같은 네트워크: `http://<이 PC IP>:4173` (Windows 방화벽에서 4173 허용 필요)

## 공개 배포 (현재)

**GitHub Pages (공개 저장소)**  
https://bdk-choi.github.io/sentinos-mobile-docs/

| 페이지 | URL |
|---|---|
| 홈 | https://bdk-choi.github.io/sentinos-mobile-docs/ |
| 기획 | https://bdk-choi.github.io/sentinos-mobile-docs/planning.html |
| 디자인 | https://bdk-choi.github.io/sentinos-mobile-docs/design.html |
| 시안 | https://bdk-choi.github.io/sentinos-mobile-docs/mockups.html |

배포 저장소: https://github.com/BDK-CHOI/sentinos-mobile-docs  

재배포:

```bash
npm run docs:build
# docs/site 내용을 sentinos-mobile-docs 저장소 main에 push
```
