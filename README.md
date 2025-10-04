# Korean Dictionary for Obsidian

한국어 단어 검색을 위한 Obsidian 플러그인입니다. 표준국어대사전 API를 사용하여 단어의 뜻을 검색하고, AI를 활용하여 한자, 유의어, 반의어, 용례를 제공합니다.

## 기능

- 표준국어대사전 API를 사용한 한국어 단어 검색
- Sidebar 및 Modal 지원
- AI 기반 한자/유의어/반의어/용례 생성
- 지원 AI(ChatGPT, Gemini, Claude, Grok)
- 텍스트 선택 시 sidebar 패널에서 자동 검색

## 설치 방법

### 수동 설치

1. BRAT에 저장소의 주소를 입력

2. 설치, 활성화해줍니다. 

## 설정

### API 키 발급

#### 표준국어대사전 API
1. [국립국어원 표준국어대사전 Open API](https://stdict.korean.go.kr/openapi/openApiInfo.do) 페이지에 접속합니다
2. 회원가입 및 로그인 후 API 키를 발급받습니다
3. 플러그인 설정에서 발급받은 API 키를 입력합니다

#### AI API (선택사항)
한자/유의어/반의어/용례 생성 기능을 사용하려면 아래 중 하나의 API 키가 필요합니다:

- **ChatGPT**: [OpenAI Platform](https://platform.openai.com/api-keys)
- **Gemini**: [Google AI Studio](https://aistudio.google.com/app/apikey)
- **Claude**: [Anthropic Console](https://console.anthropic.com/)
- **Groq**: [Groq Console](https://console.groq.com/)

### 플러그인 설정

Obsidian 설정 > 플러그인 설정 > Korean Dictionary에서 다음을 설정할 수 있습니다:

- 품사/정의: 표준국어대사전 API 키
- 한자/유의어/반의어/용례: AI 제공자, API 키, 모델 선택


## 사용 방법

### 검색 방법

1. **리본 아이콘 클릭**: 왼쪽 사이드바의 검색 아이콘을 클릭합니다
2. **명령어 팔레트**:
   - `Ctrl/Cmd + P`를 누르고 "Korean Dictionary"를 검색합니다
   - "Open dictionary in sidebar" 또는 "Open dictionary in modal" 선택
3. **텍스트 선택**:
   - 노트에서 단어를 선택합니다
   - 명령어 팔레트에서 "Search selected text in dictionary" 선택


## 라이선스

MIT

## 크레딧

- 국립국어원 표준국어대사전 Open API
- Obsidian API
