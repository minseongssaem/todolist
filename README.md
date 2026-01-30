# 🌸 BLOOMING

> 오늘도 피어나는 중

BLOOMING은 할 일 관리, 목표 설정, 습관 트래커, 레벨 시스템을 통합한 종합 생산성 관리 앱입니다.

## ✨ 주요 기능

### 📊 대시보드
- 오늘의 할 일 현황 한눈에 보기
- 현재 레벨 & 경험치 확인
- 진행 중인 목표 추적
- 최고 연속 기록 확인

### 📝 할 일 관리
- **캘린더 뷰**: 월별 캘린더로 날짜별 할 일 관리
- **두 가지 타입**: 특정 날짜 / 매일 반복
- **카테고리**: 업무, 건강, 학습, 취미, 재정, 기타
- **실시간 동기화**: Firebase 기반 실시간 반영

### 🎯 목표 관리
- **3단계 목표**: 주간, 월간, 연간
- **진행률 추적**: 슬라이더로 진행도 조절 (0-100%)
- **카테고리별 관리**: 각 목표를 카테고리로 분류
- **경험치 획득**: 목표 달성 시 50 XP

### 🔥 습관 트래커
- **연속 기록**: 며칠 연속 달성했는지 표시
- **최고 기록**: 최고 연속 기록 저장
- **일일 체크**: 하루에 한 번만 체크 가능
- **경험치 획득**: 습관 체크 시 5 XP

### 🏆 업적 & 레벨 시스템
- **레벨 시스템**: 경험치 획득으로 레벨업
- **8가지 업적**: 
  - 첫 시작 (할 일 1개 완료)
  - 열심히 (10개 완료)
  - 성실함 (50개 완료)
  - 달인 (100개 완료)
  - 초보 졸업 (Lv.5 달성)
  - 중수 (Lv.10 달성)
  - 일주일 (7일 연속)
  - 한 달 (30일 연속)
- **경험치 획득 방법**:
  - 할 일 완료: 10 XP
  - 습관 체크: 5 XP
  - 목표 100% 달성: 50 XP

## 🛠️ 기술 스택

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Firebase Realtime Database
- **Authentication**: Firebase Authentication
- **Hosting**: Vercel

## 🚀 시작하기

### 로컬 실행

1. 저장소 클론
```bash
git clone https://github.com/your-username/blooming.git
cd blooming
```

2. 웹 서버로 실행
```bash
# Python 3를 사용하는 경우
python -m http.server 8000

# Node.js의 http-server를 사용하는 경우
npx http-server
```

3. 브라우저에서 `http://localhost:8000` 접속

### Firebase 설정

Firebase 설정이 필요한 경우 `index.html` 파일의 `firebaseConfig` 부분을 수정하세요:

```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_AUTH_DOMAIN",
    databaseURL: "YOUR_DATABASE_URL",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_STORAGE_BUCKET",
    messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
    appId: "YOUR_APP_ID"
};
```

## 📱 반응형 디자인

BLOOMING은 데스크톱, 태블릿, 모바일 모든 기기에서 완벽하게 작동합니다.

## 🎨 디자인 컨셉

"피어나다"라는 의미의 BLOOMING은 따뜻한 핑크 그라데이션으로 성장과 발전을 시각적으로 표현합니다.

- **메인 컬러**: 핑크 계열 (#FFB6C1, #FF69B4, #FF1493)
- **컨셉**: 매일 조금씩 피어나는 꽃처럼 성장하는 나
- **느낌**: 따뜻하고 긍정적이며 희망찬

## 📄 라이선스

MIT License

## 👨‍💻 개발자

Made with 💖 by Your Name

## 🙏 감사의 말

이 프로젝트는 Claude AI의 도움을 받아 개발되었습니다.
