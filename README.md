# 짝을 찾아라

Electron으로 만든 숫자 메모리 카드 게임입니다. 카드를 두 장씩 뒤집어 같은 숫자끼리 짝을 맞추세요.

## 기능

- 4 × 4, 6 × 6, 8 × 8 보드 선택
- 시도 횟수와 찾은 짝 표시
- 다시 시작 버튼
- macOS와 Windows용 앱 패키징

## 실행

Node.js와 npm이 설치되어 있어야 합니다.

```bash
npm install
npm start
```

## 빌드

현재 운영체제에 맞는 산출물을 만들거나, 명시적으로 플랫폼을 선택할 수 있습니다.

```bash
npm run dist       # macOS 및 Windows용 빌드
npm run dist:mac   # macOS용 빌드
npm run dist:win   # Windows용 빌드
```

결과물은 `dist/` 디렉터리에 생성됩니다.

## 프로젝트 구성

- `main.cjs`: Electron 창과 앱 생명 주기
- `index.html`: 게임 화면, 스타일, 게임 로직
- `package.json`: 의존성, 실행 및 빌드 스크립트
