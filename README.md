# ai-deepseek

DeepSeek driver for the togo `ai` plugin — a unified LLM interface (chat + embeddings) for togo apps.

## Install
```bash
togo install togo-framework/ai-deepseek
```

## Configure
Set `AI_DRIVER=deepseek` and:
```env
DEEPSEEK_API_KEY=...
# optional: DEEPSEEK_BASE_URL=https://api.deepseek.com/v1
```

Then the `ai` plugin routes `Chat`/`Embed` through DeepSeek. Token usage is reported via `ai.Usage` (for the billing plugin).

MIT © ToGO
