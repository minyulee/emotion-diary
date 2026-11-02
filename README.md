# 🌿 오늘의 마음 (Daily Mind) | 감정 일기 & TO-DO 동기화 Web App

> **"잘 정리해서 쓰지 않아도 괜찮아요. 지금 느끼는 마음 그대로 적어보세요."**  
> 오늘의 마음은 일상 속 감정 기록, 공부 스케줄, 랜덤 질문 답변을 한곳에서 관리하고 Firebase를 통해 **TO-DO LIST와 실시간 동기화**되는 싱글 페이지 감정 일기 웹 애플리케이션입니다.

---

## 📸 미리보기 (Preview)

- **디자인 컨셉**: 눈이 편안한 네이처 톤(Soft Sage Green) & 반응형 카드 레이아웃
- **기술 스택**: Vanilla HTML5, CSS3, JavaScript (ES6+), Firebase v10 (Authentication & Firestore)
- **배포 방식**: GitHub Pages / Netlify 등 단일 HTML 파일 배포 지원

---

## ✨ 주요 기능 (Key Features)

### 1. 🎭 오늘 나의 감정 선택 (Multi-select Moods)
- 행복, 평온, 피곤, 불안, 과부하, 번아웃 등 **17가지 이상의 세분화된 감정 태그** 제공
- 복수 선택 지원으로 다채로운 나의 마음 상태를 입체적으로 기록

### 2. 📝 자유로운 일기 & 공부 기록 (Journal & Study Log)
- **실시간 글자 수 카운팅** 지원
- 공부 일지, 학습 중 느낀 점, 추가 메모를 위한 별도의 **공부 기록 전용 영역** 탑재
- 작성 중 데이터 손실 방지를 위한 **자동 저장(Debounce Save)** 탑재

### 3. 🌿 오늘의 질문 (Daily Reflection Prompts)
- 감정, 돌봄, 성장, 관계, 공부, 생각, 미래 등 **20가지 심리·회고 질문 카드로 무작위 제공**
- 질문 추첨(`다른 질문 뽑기`) 및 답변 기록 기능

### 4. ✅ 기존 TO-DO LIST와 실시간 연동 (Firebase Cloud Sync)
- 동일한 Firebase 계정으로 로그인 시, **기존 TO-DO LIST 앱의 해당 날짜 할 일 목록 자동 불러오기**
- 기기 간(모바일/PC) 일기 데이터 실시간 Cloud 동기화 (`Firestore`)

### 5. 📅 감정 달력 & 검색 (Calendar & Search)
- **감정 달력**: 일기가 작성된 날짜에 초록색 인디케이터(점) 표시 및 해당 날짜 클릭 시 기록으로 즉시 이동
- **실시간 통합 검색**: 키워드 입력 시 감정 태그, 일기 내용, 공부 기록, 질문 답변까지 한꺼번에 검색

### 6. 🔒 데이터 백업 & 개인정보 보호
- **백업 내보내기/불러오기**: `.json` 포맷 데이터 백업 및 복원 기능 제공
- **로컬 & 클라우드 ই중 저장**: 오프라인 상태에서는 `localStorage`로 안전하게 보관

---

## 🛠️ 기술 스택 (Tech Stack)

| 구분 | 사용 기술 |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (CSS Variables, Flexbox, CSS Grid), JavaScript (Vanilla ES6+) |
| **Backend / BaaS** | Firebase Authentication, Cloud Firestore |
| **Storage** | LocalStorage, Firestore Database |
| **Icon / Typography** | Native System Fonts, Unicode Emojis |

---

## 📁 파일 구조 (File Structure)

본 프로젝트는 의존성 관리자(npm/yarn) 없이 단일 HTML 파일 형태로 동작할 수 있도록 경량화되어 있습니다.

```text
.
├── index.html          # HTML 구조, CSS 스타일, Vanilla JS, Firebase SDK가 통합된 메인 파일
└── README.md           # 프로젝트 문서
