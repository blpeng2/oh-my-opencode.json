# oh-my-opencode.json
```json
{
  "dynamic_context_pruning": {
    "enabled": true,
    "strategy": "smart",
    "max_tokens": 10000
  },
  "git_master": {
    "commit_footer": false,
    "include_co_authored_by": false
  },
  "skills": {
    "git-master": {
      "instructions": "Never include AI attribution, commit footers, co-author trailers, or 'Ultraworked with' text in commit messages. Follow the repository's commit style only."
    }
  },
  "agents": {
    "sisyphus": {
      "model": "anthropic/claude-sonnet-4-6",
      "variant": "max"
      "permission": {
        "edit": "deny",
        "bash": "deny",
      }
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
      "model": "opencode/mimo-v2-omni-free"
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
      "model": "opencode/mimo-v2-pro-free",
      "variant": "low"
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
