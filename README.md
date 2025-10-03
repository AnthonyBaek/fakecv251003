# 김개발 - 소프트웨어 엔지니어 포트폴리오

> 5년 경력의 소프트웨어 엔지니어 김개발의 개인 포트폴리오 웹사이트입니다.

## 📋 프로젝트 개요

이 프로젝트는 소프트웨어 엔지니어 김개발의 개인 포트폴리오 웹사이트로, 순수 HTML, CSS, JavaScript로 제작된 반응형 원페이지 웹사이트입니다.

### 🎯 주요 특징
- **반응형 디자인**: 모바일, 태블릿, 데스크톱 모든 화면 크기 지원
- **원페이지 구조**: 스크롤 기반 네비게이션
- **인터랙티브 요소**: 애니메이션, 호버 효과, 타이핑 효과
- **현대적 UI/UX**: 그라데이션, 카드 디자인, 부드러운 전환 효과

## 🛠️ 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Font**: Noto Sans KR (Google Fonts)
- **Icons**: Emoji 및 Unicode 아이콘
- **Images**: Unsplash (무료 이미지)

## 📁 프로젝트 구조

```
portfolio-website/
├── index.html          # 메인 HTML 파일
├── style.css           # 스타일시트
├── script.js           # JavaScript 파일
├── 자기소개.txt        # 원본 데이터 파일
├── requirements.md     # 프로젝트 요구사항
└── README.md          # 프로젝트 문서
```

## 🚀 로컬 실행 방법

### 1. 파일 다운로드
```bash
# 프로젝트 클론 또는 파일 다운로드
git clone [repository-url]
cd portfolio-website
```

### 2. 로컬 서버 실행
```bash
# Python을 사용한 로컬 서버 (권장)
python -m http.server 8000

# 또는 Node.js 사용
npx http-server -p 8000

# 또는 PHP 사용
php -S localhost:8000
```

### 3. 브라우저에서 확인
```
http://localhost:8000
```

## 🌐 배포 방법

### 1. GitHub Pages (무료, 추천)

1. **GitHub 저장소 생성**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/username/portfolio-website.git
   git push -u origin main
   ```

2. **GitHub Pages 설정**
   - GitHub 저장소 → Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Save

3. **배포 완료**
   ```
   https://username.github.io/portfolio-website
   ```

### 2. Netlify (무료, 추천)

1. **Netlify 사이트 접속**: [netlify.com](https://netlify.com)
2. **회원가입/로그인**
3. **배포 방법 선택**:
   - **Drag & Drop**: `index.html` 파일을 드래그하여 업로드
   - **Git 연동**: GitHub 저장소 연결

### 3. Vercel (무료)

1. **Vercel 사이트 접속**: [vercel.com](https://vercel.com)
2. **GitHub 연동**
3. **프로젝트 import**
4. **자동 배포 완료**

### 4. Firebase Hosting

```bash
# Firebase CLI 설치
npm install -g firebase-tools

# Firebase 로그인
firebase login

# 프로젝트 초기화
firebase init hosting

# 배포
firebase deploy
```

## 📱 섹션 구성

### 1. **홈 (Home)**
- 메인 소개 및 프로필 사진
- 핵심 기술 스택 하이라이트
- CTA 버튼 (더 알아보기, 연락하기)

### 2. **소개 (About)**
- 상세 자기소개
- 핵심 통계 (경력, 프로젝트, 회사 경험, 자격증)

### 3. **경력 (Experience)**
- 타임라인 형태의 경력 표시
- ABC 테크놀로지스 (현재)
- XYZ 솔루션즈
- 스타트업 DEF

### 4. **기술 (Skills)**
- 프로그래밍 언어
- 프레임워크
- 데이터베이스
- 클라우드 & DevOps

### 5. **프로젝트 (Projects)**
- 대규모 전자상거래 플랫폼
- 금융 데이터 분석 플랫폼
- 모바일 쇼핑 앱 백엔드

### 6. **연락처 (Contact)**
- 연락처 정보
- 메시지 전송 폼

## 🎨 커스터마이징

### 색상 변경
`style.css` 파일에서 CSS 변수 수정:
```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #7c3aed;
  --accent-color: #fbbf24;
}
```

### 내용 수정
1. **개인 정보**: `index.html`의 연락처 정보 수정
2. **경력 정보**: 경력 섹션의 회사명, 기간, 업무 내용 수정
3. **프로젝트**: 프로젝트 섹션의 내용 수정
4. **이미지**: Unsplash URL을 본인 이미지로 변경

### 폰트 변경
```html
<!-- Google Fonts 링크 변경 -->
<link href="https://fonts.googleapis.com/css2?family=원하는폰트:wght@300;400;500;700&display=swap" rel="stylesheet">
```

## 🔧 성능 최적화

### 이미지 최적화
- WebP 포맷 사용 권장
- 적절한 이미지 크기 설정
- Lazy loading 적용

### CSS/JS 최적화
- CSS 압축 (minify)
- JavaScript 번들링
- 불필요한 코드 제거

## 📊 SEO 최적화

### 메타 태그 추가
```html
<meta name="description" content="김개발 - 5년 경력의 소프트웨어 엔지니어 포트폴리오">
<meta name="keywords" content="소프트웨어 엔지니어, 개발자, 포트폴리오, Java, Spring Boot, React">
<meta name="author" content="김개발">
```

### Open Graph 태그
```html
<meta property="og:title" content="김개발 - 소프트웨어 엔지니어">
<meta property="og:description" content="5년 경력의 소프트웨어 엔지니어 포트폴리오">
<meta property="og:image" content="프로필이미지URL">
```

## 🐛 문제 해결

### 일반적인 문제들

1. **로컬에서 스타일이 적용되지 않음**
   - 로컬 서버 사용 확인
   - 파일 경로 확인

2. **모바일에서 레이아웃 깨짐**
   - 뷰포트 메타 태그 확인
   - CSS 미디어 쿼리 확인

3. **이미지가 로드되지 않음**
   - 이미지 URL 확인
   - 네트워크 연결 확인

## 📞 지원

문제가 발생하거나 질문이 있으시면:
- 📧 이메일: kim.dev@email.com
- 💻 GitHub: github.com/kimdev
- 💼 LinkedIn: linkedin.com/in/kimdev

## 📄 라이선스

이 프로젝트는 개인 포트폴리오 목적으로 제작되었습니다.

---

**Made with ❤️ by 김개발**
