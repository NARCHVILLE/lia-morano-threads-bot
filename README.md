# lia-morano-threads-bot

Engagement agent for @lia.morano.oficial on Threads: monitors comments on own posts, generates responses in LIA voice, posts with optional human approval.

## Status
- Stubs for monitor and voice generation in place.
- Based on: alpersamur3/threads-bot, sorcerai/threadsponder, x-bizarre/amy-threads-bot.
- Next priority: integrate authentication (cookies or Playwright) and real comment fetching.

## Voice
See `src/lia_voice.py` for system prompt and templates. Responses should be short, conversational, never force AI disclosure.

## Roadmap
1. Connect Threads channel in Buffer (or private API).
2. Implement comment listener.
3. LLM response generation with LIA identity.
4. Approval flow or auto-post with safety checks.
5. Logging to Notion.
