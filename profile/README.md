# Notion Passport

**프로젝트마다 필요한 Notion 워크스페이스를 연결하세요.**

Notion Passport는 Claude Code와 Codex에서 프로젝트별 Notion 연결을 관리하는 오픈소스 플러그인입니다. 공식 Notion MCP와 OAuth 인증을 사용해, 각 프로젝트에 필요한 계정과 워크스페이스를 연결합니다.

## 플러그인

| 환경 | 주요 기능 | 저장소 |
| --- | --- | --- |
| Claude Code | 프로젝트마다 별도의 Notion 워크스페이스 연결 | [notion-passport-claude-code](https://github.com/notion-passport/notion-passport-claude-code) |
| Codex | 프로젝트별 독립 연결 및 한 프로젝트의 여러 계정·워크스페이스 연결 | [notion-passport-codex](https://github.com/notion-passport/notion-passport-codex) |

## 설치

### Claude Code

Claude Code에서 실행합니다.

```text
/plugin marketplace add notion-passport/notion-passport-claude-code
/plugin install notion-passport@notion-passport
```

### Codex

Codex CLI에서 실행합니다.

```sh
codex plugin marketplace add notion-passport/notion-passport-codex
codex plugin add notion-passport@personal
```

설치 후 연결할 프로젝트에서 새 대화를 시작하고, “이 프로젝트에 노션 워크스페이스를 연결해줘”라고 요청하세요. 브라우저에서 연결할 Notion 계정과 워크스페이스를 선택하면 됩니다.

자세한 사용법과 요구사항은 각 저장소의 README를 확인하세요. 버그 제보와 개선 제안은 해당 저장소의 Issues에서 받습니다.
