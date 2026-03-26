# oh-my-opencode.jsonc
```json
{
  "$schema": "https://raw.githubusercontent.com/code-yeongyu/oh-my-opencode/master/assets/oh-my-opencode.schema.json",
  "disabled_hooks": ["todo-continuation-enforcer", "gpt-permission-continuation"],
  "git_master": {
    "commit_footer": false,
    "include_co_authored_by": false
  },
  "hashline_edit": false,
  "agents": {
    "sisyphus": {
      "model": "anthropic/claude-opus-4-6",
      "variant": "max"
    },
    "hephaestus": {
      "disable": true
    },
    "oracle": {
      "model": "openai/gpt-5.4",
      "variant": "high"
    },
    "librarian": {
      "model": "opencode-go/minimax-m2.7"
    },
    "explore": {
      "model": "github-copilot/grok-code-fast-1"
    },
    "multimodal-looker": {
      "model": "openai/gpt-5.4",
      "variant": "medium"
    },
    "prometheus": {
      "model": "anthropic/claude-sonnet-4-6",
      "variant": "max"
    },
    "metis": {
      "model": "anthropic/claude-sonnet-4-6",
      "variant": "max"
    },
    "momus": {
      "model": "openai/gpt-5.4",
      "variant": "xhigh"
    },
    "atlas": {
      "model": "anthropic/claude-sonnet-4-6",
      "variant": "max"
    }
  },
  "categories": {
    // UI/UX, CSS, 스타일링, 애니메이션, 레이아웃, 디자인 구현
    "visual-engineering": {
      "model": "github-copilot/gemini-3.1-pro-preview",
      "variant": "high"
    },
    // 고난이도 로직, 알고리즘, 아키텍처 설계 (순수 추론력)
    "ultrabrain": {
      "model": "openai/gpt-5.4",
      "variant": "xhigh"
    },
    // 자율 리서치 → 구현. 깊은 이해가 필요한 복잡한 문제 (연구원 방법론)
    "deep": {
      "model": "openai/gpt-5.3-codex"
    },
    // 비정형 창의적 문제해결. 표준 패턴을 넘어서는 접근
    "artistry": {
      "model": "github-copilot/gemini-3.1-pro-preview",
      "variant": "high"
    },
    // 단일 파일 수정, 오타, 간단한 변경
    "quick": {
      "model": "openai/gpt-5.4-mini",
      "variant": "medium"
    },
    "unspecified-low": {
      "model": "anthropic/claude-sonnet-4-6"
    },
    "unspecified-high": {
      "model": "anthropic/claude-opus-4-6"
    },
    // 문서, 산문, 기술 문서 작성
    "writing": {
      "model": "github-copilot/gemini-3-flash-preview"
    }
  }
}

```

# opencode.json

```json
{
  "$schema": "https://opencode.ai/config.json",
  "plugin": [
    "oh-my-opencode@",
    "@franlol/opencode-md-table-formatter",
    "opencode-claude-auth",
    "opencode-openai-codex-auth"
  ],
  "provider": {
    "openai": {
      "name": "OpenAI",
      "models": {
        "gpt-5.4": {
          "options": {
            "serviceTier": "priority"
          }
        }
      }
    }
  }
}
```

