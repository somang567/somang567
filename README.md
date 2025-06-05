
> 💡 실제로 사용하고 싶은 프로젝트명, 설명, 스택에 맞게 바꿔 드릴 수 있어요. 원하시면 작업해드릴게요.

---

## ✅ 2. GitHub Pages로 폰트도 마음대로 설정하기

### 🔧 방법 요약

1. GitHub에 새 레포 만들기 (예: `somang567.github.io`)
2. `index.html` 파일에 원하는 폰트 CSS 추가
3. GitHub Pages 설정에서 **Main 브랜치** 선택
4. 몇 분 뒤 `https://somang567.github.io`에서 확인 가능

---

### 🎨 예시 `index.html` (폰트 변경 포함)

```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>Somang's Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Nanum+Pen+Script&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Nanum Pen Script', cursive;
      font-size: 24px;
      background: #fffaf0;
      padding: 40px;
    }
  </style>
</head>
<body>
  <h1>안녕하세요! 솜앙입니다 👋</h1>
  <p>이 페이지는 나만의 글꼴로 꾸민 GitHub 페이지입니다!</p>
</body>
</html>
