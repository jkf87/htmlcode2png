# HTML to PNG 변환기

HTML 코드를 고품질 PNG 이미지로 변환하는 웹 애플리케이션입니다.

## 🌐 데모

**[https://jkf87.github.io/htmlcode2png/](https://jkf87.github.io/htmlcode2png/)**

## ✨ 주요 기능

- **HTML 코드 입력**: 텍스트 영역에 HTML 코드를 직접 붙여넣기
- **실시간 미리보기**: 변환 전 HTML 렌더링 결과를 미리 확인
- **고품질 변환**: html2canvas 라이브러리를 사용한 선명한 PNG 이미지 생성
- **즉시 다운로드**: 변환된 PNG 파일을 바로 다운로드
- **테스트 샘플**: 내장된 샘플 HTML로 기능 테스트 가능
- **반응형 디자인**: 모바일과 데스크톱에서 모두 사용 가능

## 🚀 사용법

1. 웹사이트에 접속합니다
2. 왼쪽 텍스트 영역에 HTML 코드를 붙여넣습니다
3. **"테스트 HTML 로드"** 버튼으로 샘플 코드를 확인할 수 있습니다
4. **"PNG로 변환"** 버튼을 클릭합니다
5. 오른쪽 미리보기에서 결과를 확인합니다
6. **"PNG 다운로드"** 버튼으로 이미지를 저장합니다

## 🛠️ 기술 스택

- **HTML5**: 웹 구조
- **CSS3**: Tailwind CSS를 사용한 스타일링
- **JavaScript**: 동적 기능 구현
- **html2canvas**: HTML을 Canvas로 변환
- **Google Fonts**: Noto Sans KR 폰트

## 📁 파일 구조

```
htmlcode2png/
├── index.html          # 메인 웹 애플리케이션
├── test.html          # 테스트용 샘플 HTML
└── README.md          # 프로젝트 문서
```

## 💡 특징

### 고품질 렌더링
- iframe을 사용한 독립적인 HTML 렌더링 환경
- 외부 CSS 및 JavaScript 지원
- 폰트와 이미지 로딩 대기 시간 최적화

### 사용자 친화적 인터페이스
- 직관적인 2단 레이아웃
- 실시간 로딩 인디케이터
- 명확한 사용법 안내

### 브라우저 호환성
- 모든 모던 브라우저에서 작동
- CORS 정책을 고려한 안전한 이미지 처리

## 🔧 로컬 개발

1. 저장소를 클론합니다:
```bash
git clone https://github.com/jkf87/htmlcode2png.git
cd htmlcode2png
```

2. 웹 서버를 실행합니다:
```bash
# Python을 사용하는 경우
python -m http.server 8000

# Node.js를 사용하는 경우
npx http-server
```

3. 브라우저에서 `http://localhost:8000`에 접속합니다

## 📝 사용 예시

### 기본 HTML
```html
<!DOCTYPE html>
<html>
<head>
    <title>My Page</title>
    <style>
        body { font-family: Arial; padding: 20px; }
        h1 { color: #333; }
    </style>
</head>
<body>
    <h1>안녕하세요!</h1>
    <p>HTML to PNG 변환 테스트입니다.</p>
</body>
</html>
```

### Tailwind CSS 사용
```html
<!DOCTYPE html>
<html>
<head>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-blue-100 p-8">
    <div class="bg-white rounded-lg shadow-lg p-6">
        <h1 class="text-2xl font-bold text-gray-800">제목</h1>
        <p class="text-gray-600 mt-4">내용입니다.</p>
    </div>
</body>
</html>
```

## ⚠️ 제한사항

- 일부 복잡한 CSS 애니메이션은 정적 이미지로 변환됩니다
- 외부 리소스(이미지, 폰트 등)는 CORS 정책에 따라 제한될 수 있습니다
- 매우 큰 HTML 페이지는 변환 시간이 오래 걸릴 수 있습니다

## 🤝 기여하기

1. Fork 저장소
2. 새 기능 브랜치 생성 (`git checkout -b feature/새기능`)
3. 변경사항 커밋 (`git commit -am '새 기능 추가'`)
4. 브랜치에 Push (`git push origin feature/새기능`)
5. Pull Request 생성

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 🔗 관련 링크

- [html2canvas 라이브러리](https://html2canvas.hertzen.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [GitHub Pages](https://pages.github.com/)

---

⭐ 이 프로젝트가 유용하다면 스타를 눌러주세요!