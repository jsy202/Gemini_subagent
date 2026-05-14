# Gemini Subagents

This repository contains custom subagents for the Gemini CLI.

## Installation

To use these subagents, copy the `.md` files to your Gemini agents directory. 

**Note: Do not use symbolic links, as the Gemini CLI may not recognize them.**

### User-level (Global)
Copy the files to `~/.gemini/agents/`:

```bash
cp *.md ~/.gemini/agents/
```

### Project-level (Local)
Copy the files to `.gemini/agents/` in your project root:

```bash
mkdir -p .gemini/agents
cp *.md .gemini/agents/
```

## Available Subagents

- **research_critical-strengthener**: 비판 및 강화 전문가. 주제의 논리적 허점을 찾고 더 강력한 주제로 발전시킵니다.
- **research_evidence-verifier**: 증거 검증 전문가. 선행 연구 및 데이터 가용성을 확인합니다.
- **research_final-planner**: 최종 계획 전문가. 연구 계획서 초안을 기획합니다.
- **research_topic-creator**: 주제 생성 전문가. 창의적이고 구체적인 연구 주제 후보를 생성합니다.
- **user_code-verifier**: 코드 검증 전문가. 버그, 보안, 성능 등을 식별합니다.
- **user_final-summarizer**: 최종 정리 전문가. 전체 작업 과정을 종합하여 보고서를 제공합니다.
- **user_fix-expert**: 수정 전문가. 안전하고 최소한의 변경으로 코드를 수정합니다.
- **user_test-designer**: 테스트 설계 전문가. 테스트 전략을 설계합니다.
