# My Hermes — Coder Profile

Development-focused Hermes profile with Agnes AI, GitHub MCP, code review, and Cloudflare tools.

## What's Included

- **Agnes AI Integration**: Image/video generation (agnes-image-2.1-flash, agnes-video-2.5-flash)
- **GitHub MCP**: Native GitHub tools (issues, PRs, code review)
- **GitHub Skills**: Auth, PR workflow, issues, code review, repo management
- **Cloudflare Skills**: Workers, Durable Objects, Sandbox, Turnstile, Email, One
- **Custom Plugins**: `image_gen/agnes` and `video_gen/agnes`

## Quick Install

```bash
hermes profile install github.com/WanderleeDev/my-hermes-profile-coder --alias
```

Then fill in your `.env`:
```bash
cp .env.example .env
# Edit .env with your API keys
```

## Requirements

- Hermes Agent >= 0.12.0
- Agnes AI API key (https://agnes-ai.com)
- GitHub token (for MCP)

## Author

WanderleeDev

## License

MIT
