# 👨‍⚕️ 온선생 (OnSunsaeng)

노인을 위한 음성 기반 건강 모니터링 어플리케이션  
AI 비서가 매일 건강 상태를 체크하고, 고위험군 판단 시 병원 안내까지 도와드려요.

---

## 📌 프로젝트 소개

‘온선생’은 노인 사용자를 위한 **AI 기반 건강 체크 앱**입니다.  
음성 인식으로 사용자의 건강 상태를 파악하고, **GPT 모델**을 통해 증상을 분석해 친절하게 피드백합니다.

💡 고위험군이 의심되면, 2차 질문을 통해 심층 확인 후 **119 연결 기능**까지 제공합니다.

---

## 📱 주요 기능

| 기능 구분 | 설명 |
|----------|------|
| 🎤 음성 입력 | "오늘 어디가 불편하세요?" 질문에 대한 음성 응답 인식 |
| 🧠 GPT 분석 | 어르신 말씀을 자연어로 GPT가 요약 및 판단 |
| 🚨 고위험 감지 | 심근경색 등 의심 시, 응급 알림 및 2차 질문 |
| 📞 응급 연결 | 위험 판단 시, 119로 즉시 연결 |
| 📝 일상 기록 | 사용자의 발화 기록을 자동 저장 (기록 기능 연동 예정) |

---

## 🧠 사용 기술 스택

- **Frontend**: React Native (TypeScript)
- **AI 분석**: OpenAI GPT-3.5 Turbo
- **음성 인식**: react-native-voice
- **디자인**: Flat UI + Senior Friendly UX
- **iOS 빌드**: Xcode, Apple Developer Account

---

## 🛠️ 설치 및 실행

```bash
# 의존성 설치
npm install

# iOS 시뮬레이터 실행
npx react-native run-ios

# 실제 디바이스 실행 (팀 설정 필요)
npx react-native run-ios --device "YOUR_DEVICE_NAME"
