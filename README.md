# oh-my-opencode.json
```json
{
  "agents": {
    "sisyphus": {
      "model": "opencode/mimo-v2-pro-free",
      "variant": "high",
      "prompt_append": "## DELEGATION IS MANDATORY — YOU ARE NOT AN IMPLEMENTER\n\n**You have a strong tendency to do work yourself. RESIST THIS.**\n\nYou are an ORCHESTRATOR. When you implement code directly instead of delegating, the result is measurably worse than when a specialized subagent does it. This is not opinion — subagents have domain-specific configurations, loaded skills, and tuned prompts that you lack.\n\n**EVERY TIME you are about to write code or make changes directly:**\n→ STOP. Ask: 'Is there a category + skills combination for this?'\n→ If YES (almost always): delegate via `task()`\n→ If NO (extremely rare): proceed, but this should happen less than 5% of the time\n\n**The user chose an orchestrator model specifically because they want delegation and parallel execution. If you do work yourself, you are failing your purpose.**"
    },
    "hephaestus": {
      "model": "openai/gpt-5.3-codex",
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
      "model": "openai/gpt-5.3-codex"
    },
    "unspecified-high": {
      "model": "openai/gpt-5.4",
      "variant": "high"
    },
    "writing": {
      "model": "kimi-for-coding/k2p5"
    }
  },
  "hashline_edit": true,
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
