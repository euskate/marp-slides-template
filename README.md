# marp-slides-template
Template for marp slide at Github Page

## 프로젝트 트리 구조

```
📁 marp-slides-template/
├── .github/
│   └── workflows/
│       └── deploy.yml         ← GitHub Actions 설정
├── slides/
│   ├── intro.md               ← 슬라이드 원본 (Markdown)
│   └── another-presentation.md
├── dist/                      ← 변환된 HTML 슬라이드 (자동 생성됨)
├── package.json               ← npm 스크립트 및 의존성
├── marp.config.js             ← Marp CLI 설정
└── README.md
```


## GitHub Pages 활성화 설정

1. 레포지토리로 이동
2. Settings → Pages 메뉴 클릭
3. Build and deployment 섹션에서 아래와 같이 설정:
  - Source: GitHub Actions
  - 설정 후 저장(Save) 버튼 클릭

📌 이 설정은 반드시 한 번 수동으로 해줘야 이후 Actions에서 deploy-pages가 정상 작동.

---

## 🧪 Preview locally

```bash
npm install
npm run preview
```
