# Detailed Explanation of Open Source Tools

## Links

- https://www.kevnu.com/en/posts/the-ultimate-comparison-of-claude-code-alternatives-a-complete-analysis-of-the-10-strongest-cli-ai-programming-tools


_____________
## 1. Gemini CLI 

Official Repository: https://github.com/google-gemini/gemini-cli

Core Advantages
- Completely Free: 60 requests per minute, 1,000 requests per day for personal Google accounts
- Massive Context: Native support for 1 million token context window with Gemini 2.5 Pro
- Multimodal Capabilities: Supports various inputs including text, images, PDFs, and videos
- Google Search Integration: Real-time access to web pages and latest information
- MCP Support: Built-in Model Context Protocol support
- Fully Open Source: Apache 2.0 license, transparent code

Installation Method
```
# NPM Installation (requires Node.js 18+)
npm install -g @google/gemini-cli

# Verify installation
gemini --version
```

Authentication Configuration  
Method 1: Personal Google Account (Free, Recommended)
```
# Automatic authentication guide on first run
gemini

# Log in to your Google account as prompted

```

Basic Usage
```
# Launch Gemini CLI
gemini

# Programmatic mode
gemini -p "Create a REST API"

# JSON output
gemini -p "Analyze code architecture" --output-format json

```

Advanced Configuration  
Project Context (Create GEMINI.md or use /init to automatically summarize and generate)
```
# Project Guidelines

## Tech Stack

- React 18 with TypeScript
- Tailwind CSS for styling
- Vitest for testing

## Code Style

- Use functional components
- Follow Airbnb style guide
- Add JSDoc comments

```

MCP Server Configuration (~/.gemini/settings.json)
```
{
  "mcpServers": {
    "github": {
      "transport": "stdio",
      "command": "npx",
      "args": ["@modelcontextprotocol/server-github"]
    }
  }
}

```

Free Quota
- Personal Account: 60 RPM / 1,000 RPD
- Completely Free: No credit card required  


___________________

## 2. Aider

## 3. OpenCode

## 4. Qwen Code

## 5. Crush

## 6. Kimi CLI 

## 7. Codex CLI (OpenAI)

## 8. Grok CLI 



