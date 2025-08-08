# 과학기술 발전사 타임라인 📚

인류 역사상 중요한 과학기술 발전을 시각적으로 보여주는 인터랙티브 타임라인입니다.

## 🌟 주요 기능

- **인터랙티브 타임라인**: 기원전 330만년부터 2025년까지의 과학기술 발전사
- **다크/라이트 모드**: 사용자 선호에 따른 테마 전환
- **연도별 네비게이션**: 특정 연도로 빠른 이동
- **분야별 필터링**: 컴퓨터, 의학, 물리학 등 분야별 검색
- **반응형 디자인**: 모바일, 태블릿, 데스크톱 지원
- **부드러운 애니메이션**: 스크롤 기반 fade-in 효과

## 🚀 라이브 데모

[GitHub Pages에서 확인하기](https://yourusername.github.io/historicaltechtree/)

## 📁 프로젝트 구조

```
historicaltechtree/
├── timeline.html          # 메인 HTML 파일
├── timeline-data.json     # 타임라인 데이터
├── package.json          # 프로젝트 설정
├── README.md             # 프로젝트 문서
└── .gitignore           # Git 무시 파일
```

## 🛠 로컬 개발

### 1. 저장소 클론
```bash
git clone https://github.com/yourusername/historicaltechtree.git
cd historicaltechtree
```

### 2. 로컬 서버 실행
```bash
# Python 3 사용
python3 -m http.server 8000

# 또는 Node.js 사용
npx serve .
```

### 3. 브라우저에서 확인
```
http://localhost:8000/timeline.html
```

## 📊 데이터 구조

`timeline-data.json` 파일의 각 항목은 다음 구조를 가집니다:

```json
{
  "year": 2025,
  "title": "GPT-5 AI Model",
  "description": "OpenAI releases GPT-5...",
  "field": "Computer Science",
  "impact": "Revolutionary",
  "source": "https://example.com"
}
```

## 🎨 커스터마이징

### 색상 테마 변경
`timeline.html`의 CSS 변수를 수정하여 색상을 변경할 수 있습니다:

```css
:root {
  --bg-primary: #f5f3f0;
  --text-primary: #312927;
  --accent-color: #123300;
  /* ... */
}
```

### 새로운 데이터 추가
`timeline-data.json`에 새로운 항목을 추가하고 `totalItems` 수를 업데이트하세요.

## 🚀 GitHub Pages 배포

### 1. GitHub 저장소 생성
- GitHub에서 새 저장소 생성
- 저장소명: `historicaltechtree` (또는 원하는 이름)

### 2. 코드 업로드
```bash
git init
git add .
git commit -m "Initial commit: Historical Tech Timeline"
git branch -M main
git remote add origin https://github.com/yourusername/historicaltechtree.git
git push -u origin main
```

### 3. GitHub Pages 활성화
1. 저장소 → Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: "main" 선택
4. Folder: "/ (root)" 선택
5. Save 클릭

### 4. 배포 확인
- 몇 분 후 `https://yourusername.github.io/historicaltechtree/timeline.html`에서 확인

## 🔧 기술 스택

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Tailwind CSS (CDN)
- **Data**: JSON
- **Deployment**: GitHub Pages

## 📝 라이선스

MIT License - 자유롭게 사용, 수정, 배포 가능합니다.

## 🤝 기여하기

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 문의

프로젝트에 대한 질문이나 제안사항이 있으시면 이슈를 생성해 주세요.

---

⭐ 이 프로젝트가 유용하다면 스타를 눌러주세요!