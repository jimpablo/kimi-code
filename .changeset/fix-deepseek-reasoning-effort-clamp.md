---
"@moonshot-ai/kimi-code": patch
---

Fix `xhigh`/`max` thinking effort being incorrectly clamped to `high` for non-OpenAI models (DeepSeek, Qwen, etc.) when using the `openai` provider type.
