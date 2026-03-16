# oh-my-opencode.json
```json
{
  "agents": {
    "sisyphus": {
      "model": "kimi-for-coding/k2p5",
      "variant": "max"
    },
    "hephaestus": {
      "model": "openai/gpt-5.4",
      "variant": "medium"
    },
    "oracle": {
      "model": "openai/gpt-5.4",
      "variant": "high"
    },
    "librarian": {
      "model": "opencode/minimax-m2.5-free"
    },
    "explore": {
      "model": "github-copilot/grok-code-fast-1"
    },
    "multimodal-looker": {
      "model": "openai/gpt-5.4",
      "variant": "medium"
    },
    "prometheus": {
      "model": "anthropic/claude-opus-4-6",
      "variant": "max"
    },
    "metis": {
      "model": "anthropic/claude-opus-4-6",
      "variant": "max"
    },
    "momus": {
      "model": "openai/gpt-5.4",
      "variant": "high"
    },
    "atlas": {
      "model": "anthropic/claude-sonnet-4-6"
    }
  },
  "categories": {
    "visual-engineering": {
      "model": "github-copilot/gemini-3.1-pro-preview"
    },
    "ultrabrain": {
      "model": "openai/gpt-5.3-codex",
      "variant": "xhigh"
    },
    "deep": {
      "model": "openai/gpt-5.3-codex",
      "variant": "medium"
    },
    "artistry": {
      "model": "github-copilot/gemini-3.1-pro-preview"
    },
    "quick": {
      "model": "anthropic/claude-haiku-4-5"
    },
    "unspecified-low": {
      "model": "anthropic/claude-sonnet-4-6"
    },
    "unspecified-high": {
      "model": "anthropic/claude-opus-4-6"
    },
    "writing": {
      "model": "github-copilot/gemini-3-flash-preview"
    }
  },
  "hashline_edit": true,
  "dynamic_context_pruning": {
    "enabled": true,
    "strategy": "smart",
    "max_tokens": 10000
  },
  "git_master": {
    "commit_footer": "",
    "include_co_authored_by": false
  },
  "skills": {
    "git-master": {
      "instructions": "Never include AI attribution, commit footers, co-author trailers, or 'Ultraworked with' text in commit messages. Follow the repository's commit style only."
    }
  }
}

```
