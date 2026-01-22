# 🪿 goose AI 코딩 에이전트 가이드

<div align="center">

![Goose](https://img.shields.io/badge/goose-AI%20Agent-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

**오픈소스 AI 코딩 에이전트 goose 완벽 가이드**

</div>

---

## 📖 프로젝트 개요

이 프로젝트는 **goose AI 코딩 에이전트**의 사용법을 안내하는 티스토리 블로그 콘텐츠와 예제 파일들을 포함합니다.

goose는 소프트웨어 개발을 자동화하는 오픈소스 AI 에이전트로, 다음과 같은 특징이 있습니다:

- 🆓 **완전 무료 오픈소스**
- 🤖 **다양한 LLM 지원** (OpenAI, Anthropic, Tetrate, OpenRouter 등)
- 🔌 **확장 가능한 아키텍처** (MCP 서버 지원)
- 💻 **데스크톱 & CLI 버전 제공**

## 📁 프로젝트 구조

```
goose-ai-agent/
├── goose-ai-agent-guide.html    # 티스토리 블로그 HTML (한국어)
├── prompts-examples.txt          # 25개 실전 프롬프트 예제
├── goose-config-example.yaml     # 설정 파일 예제
├── .goosehints                   # goose 힌트 파일
└── README.md                     # 이 파일
```

## 🚀 빠른 시작

1. **goose 설치**
   ```bash
   # CLI 설치 스크립트 (macOS/Linux)
   curl -fsSL https://github.com/block/goose/releases/download/stable/download_cli.sh | bash

   # Homebrew (macOS)
   brew install --cask block-goose  # 데스크톱
   brew install block-goose-cli        # CLI만

   # Linux .deb 패키지
   sudo dpkg -i goose-*.deb
   ```

2. **프로바이더 설정**
   - Tetrate Agent Router ($10 무료 크레딧 제공)
   - Z.AI GLM-4.7 (오픈소스 고성능 모델)
   - OpenRouter, OpenAI, Anthropic 등 지원

3. **세션 시작**
   ```bash
   goose
   ```

## 📚 블로그 포스트

상세한 사용법은 [`goose-ai-agent-guide.html`](./goose-ai-agent-guide.html)를 참고하세요.

**주요 내용:**
- goose 개요 및 특징
- 데스크톱/CLI 설치 방법
- LLM 프로바이더 설정 (Tetrate 무료 크레딧 활용)
- 세션 시작 및 프롬프트 작성 가이드
- 확장 프로그램 활용 (Computer Controller 등)
- 실전 예제: 틱택토 게임 만들기

## 💡 프롬프트 예제

[`prompts-examples.txt`](./prompts-examples.txt)에서 25개의 실전 프롬프트를 확인하세요:

```bash
# 웹 게임 만들기
create an interactive browser-based tic-tac-toe game in javascript where a player competes against a bot

# REST API 만들기
Python FastAPI로 사용자 인증 REST API를 만들어줘. JWT 토큰을 사용하고, 회원가입, 로그인, 로그아웃 기능을 포함해줘.

# 코드 리팩토링
이 코드를 더 효율적으로 리팩토링해줘. 특히 성능 최적화와 가독성을 개선해줘.
```

## ⚙️ 설정 예제

[`goose-config-example.yaml`](./goose-config-example.yaml)를 참고하여 프로바이더와 확장 프로그램을 설정하세요.

## 🔗 유용한 링크

- [goose 공식 문서](https://block.github.io/goose/)
- [goose GitHub](https://github.com/block/goose)
- [Tetrate Agent Router](https://tetrate.io/)
- [GitHub 레포지토리](https://github.com/jmpark333/goose-ai-agent)

## 📝 라이선스

MIT License - 자유롭게 사용 및 수정 가능합니다.

---

<div align="center">

Made with ❤️ by [jmpark333](https://github.com/jmpark333)

</div>
