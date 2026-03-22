# oh-my-opencode.json
```json
{
  "$schema": "https://raw.githubusercontent.com/code-yeongyu/oh-my-opencode/master/assets/oh-my-opencode.schema.json",
  "disabled_hooks": ["todo-continuation-enforcer", "gpt-permission-continuation"],
  "git_master": {
    "commit_footer": false,
    "include_co_authored_by": false
  },
  "hashline_edit": true,
  "agents": {
    "sisyphus": {
      "model": "anthropic/claude-opus-4-6",
      "variant": "max",
      "permission": {
        "edit": "deny",
        "bash": "deny"
      },
      "prompt_append": "[important] you don't use edit and bash tool, you must call task() for everything in background."
    },
    "hephaestus": {
      "disable": true
    },
    "oracle": {
      "model": "openai/gpt-5.4",
      "variant": "high"
    },
    "librarian": {
      "model": "opencode/minimax-m2.5-free"
    },
    "explore": {
      "model": "opencode/minimax-m2.5-free"
    },
    "multimodal-looker": {
      "model": "openai/gpt-5.4"
    },
    "prometheus": {
      "model": "openai/gpt-5.4"
    },
    "metis": {
      "model": "openai/gpt-5.4"
    },
    "momus": {
      "model": "openai/gpt-5.4",
      "variant": "medium"
    },
    "atlas": {
      "model": "anthropic/claude-sonnet-4-6",
      "variant": "max"
    }
  },
  "categories": {
    "visual-engineering": {
      "model": "github-copilot/gemini-3.1-pro-preview"
    },
    "ultrabrain": {
      "model": "openai/gpt-5.4"
    },
    "deep": {
      "model": "openai/gpt-5.3-codex"
    },
    "artistry": {
      "model": "github-copilot/gemini-3.1-pro-preview"
    },
    "quick": {
      "model": "github-copilot/gpt-5.4-mini"
    },
    "unspecified-low": {
      "model": "opencode/mimo-v2-pro-free",
      "variant": "medium"
    },
    "unspecified-high": {
      "model": "opencode/mimo-v2-pro-free",
      "variant": "high"
    },
    "writing": {
      "model": "kimi-for-coding/k2p5"
    }
  }
}
```

```json
{
  "$schema": "https://opencode.ai/config.json",
  "plugin": [
    "oh-my-opencode@latest",
    "@franlol/opencode-md-table-formatter",
    "opencode-claude-auth"
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

