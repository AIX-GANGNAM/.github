
# 미러그램 (Mirrorgram)

## 📱 프로젝트 소개

미러그램은 AI 기반의 소셜 네트워킹 앱으로, 사용자의 감정을 기록하고 AI 페르소나와 상호작용할 수 있는 혁신적인 플랫폼입니다. 사용자의 사진으로 개인화된 AI 페르소나를 생성하고, 이를 통해 감정적 교류와 소통을 할 수 있습니다.

### 🎯 주요 기능

#### 1. AI 페르소나 생성 및 대화
- InstantID와 ipadapter 기술을 활용한 맞춤형 캐릭터 생성
- GPT-4 기반의 자연스러운 대화 시스템
- 사용자의 성격과 취향을 반영한 페르소나 커스터마이징

#### 2. 감정 기록 및 분석
- 텍스트, 이미지 기반 감정 분석
- 주간/월간 감정 트렌드 리포트
- AI 기반 맞춤형 음악 추천

#### 3. 소셜 네트워킹
- 페르소나 간 소통 기능
- 실시간 알림 시스템
- 친구 찾기 및 팔로우 기능

### 🛠 기술 스택

#### 프론트엔드
- React Native / Expo
- Redux Toolkit (상태관리)
- React Navigation
- Firebase Auth

#### 백엔드
- FastAPI
- Firebase
- MongoDB

#### AI/ML
- OpenAI GPT-4
- TensorFlow.js
- InstantID
- RAG (Retrieval-Augmented Generation)

### 📂 프로젝트 구조
```python:src/backend/main.py
startLine: 114
endLine: 130
```

### 🔧 설치 및 실행

1. 저장소 클론
```bash
git clone https://github.com/your-username/mirrorgram.git
```

2. 의존성 설치
```bash
cd mirrorgram
npm install
```

3. 환경변수 설정
```bash
cp .env.example .env
# .env 파일에 필요한 키 입력
```

4. 개발 서버 실행
```bash
npm start
```

### 🎨 주요 UI/UX 특징

1. 직관적인 페르소나 관리
- 스와이프 기반의 페르소나 전환
- 실시간 감정 상태 표시
- 맞춤형 프로필 커스터마이징

2. 감정 시각화
- 감정 그래프 및 차트
- 컬러 테마 기반 감정 표현
- 인터랙티브 타임라인

### 🔐 보안 및 프라이버시

- End-to-End 암호화 적용
- OAuth 2.0 인증
- GDPR 준수 데이터 처리

### 🤝 기여 방법

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### 📝 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

### 👥 팀 정보

- 홍길동 - 프론트엔드 개발
- 김철수 - 백엔드 개발
- 이영희 - AI/ML 엔지니어
- 박지민 - UI/UX 디자이너

### 📞 문의하기

프로젝트에 대한 문의나 제안사항이 있으시다면 아래로 연락해주세요:

- Email: contact@mirrorgram.com
- Issue: [https://github.com/your-username/mirrorgram/issues](https://github.com/your-username/mirrorgram/issues)
