# DALL-E 3 Image Generator

OpenAI DALL-E 3 API를 사용한 이미지 생성 웹 애플리케이션

## 기술 스택
- Frontend: React
- Backend: Express + OpenAI API

## 설치 및 실행

### 1. 환경 설정
서버 디렉토리에 `.env` 파일 생성:
```
OPENAI_API_KEY=your_api_key
```

### 2. 의존성 설치
```bash
# Frontend
cd front
yarn install

# Backend
cd server
yarn install
```

### 3. 실행
```bash
# Backend (포트 3005)
cd server
node index.js

# Frontend (포트 3000)
cd front
yarn start
```

## 사용법
1. 텍스트 프롬프트 입력
2. Submit 버튼 클릭
3. 생성된 이미지 확인