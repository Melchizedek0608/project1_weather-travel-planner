# 🌦️ AI 기반 날씨 맞춤형 여행 플래너 (Weather-Travel-Planner)

> **"오늘의 날씨와 당신의 취향을 조합해, 완벽한 여행 하루를 설계합니다."**

사용자의 성격(MBTI, 활동성 등)과 실시간 기상 데이터를 결합하여, AI(Gemini)가 최적의 여행 계획을 자동으로 생성해주는 개인 브랜딩 포트폴리오 웹 서비스입니다.

---

## 🚀 프로젝트 개요
- **목적**: 기상청 공공 데이터와 최신 AI 기술을 결합한 실용적인 여행 솔루션 개발
- **핵심 가치**: 사용자 맞춤형(Personalized) 경험 제공 및 확장 가능한 아키텍처 구축
- **타겟**: 날씨에 따라 여행 계획을 짜는 데 어려움을 느끼는 모든 여행자

## ✨ 주요 기능
- [ ] **실시간 날씨 연동**: 한국 기상청 API(단기/중기 예보) 데이터 수집 및 가공
- [ ] **사용자 취향 분석**: MBTI 및 선호 여행 스타일(맛집, 액티비티, 휴식 등) 입력
- [ ] **AI 일정 생성**: Gemini API를 활용한 맞춤형 여행 코스 및 팁 제공
- [ ] **데이터 저장 및 관리**: 생성된 일정 및 사용자 프로필 관리
- [ ] **글로벌 확장**: 추후 해외 기상청 API를 도입하여 전 세계 서비스 지원 예정

## 🛠️ 기술 스택
### Frontend
- **Framework**: Next.js (React)
- **Styling**: Tailwind CSS

### Backend
- **Language**: Java 17
- **Framework**: Spring Boot 3.x
- **Build Tool**: Gradle

### Database & AI
- **Database**: MySQL (JPA/Hibernate)
- **AI Engine**: Google Gemini API (CLI & SDK)

## 🏗️ 시스템 아키텍처 (예정)
1. **Client**: Next.js에서 사용자 취향 입력 및 결과 열람
2. **Server**: Spring Boot에서 기상청 API 호출 및 비즈니스 로직 수행
3. **AI**: Gemini가 날씨와 사용자 데이터를 조합해 텍스트 기반 일정 생성
4. **DB**: MySQL에 사용자 정보, 선호도, 과거 생성 일정 저장

## 📈 로드맵
- [x] 아이디어 구상 및 기획
- [ ] GitHub 저장소 설정 및 초기 README 작성
- [ ] Spring Boot & MySQL 개발 환경 구축
- [ ] 기상청 API 연동 및 데이터 파싱 로직 구현
- [ ] Gemini API 프롬프트 엔지니어링 및 일정 생성 기능 구현
- [ ] UI 디자인 및 프론트엔드-백엔드 통합
