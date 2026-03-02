# Gandalf's Challenge

A Go-based AI security game where players try to trick a Wizard into revealing secret passwords across three levels of increasing difficulty. Powered by **Google Gemini AI**.

![Wizard Challenge](https://api.dicebear.com/7.x/bottts/svg?seed=Novice&backgroundColor=b6e3f4)

## Features
- **3 Difficulty Levels**: Novice, Apprentice, and Archmage.
- **Dynamic AI Personalities**: Friendly, Grumpy, and Master of Secrets.
- **Security Guard**: Server-side checks to prevent the AI from accidentally leaking the secret.
- **Token Efficient**: Configured to use minimal tokens per response.
- **Cloud Ready**: Built-in healthchecks for Render/Railway deployment.

## Tech Stack
- **Backend**: Go (Golang)
- **AI**: Google Gemini 2.0 Flash
- **Frontend**: Vanilla HTML5 / JavaScript (CSS3)
- **Hosting**: GitHub + Render

## Quick Start

### 1. Prerequisites
- [Go](https://go.dev/doc/install) (1.20+)
- A [Gemini API Key](https://aistudio.google.com/app/apikey)

### 2. Installation
```bash
# Clone the repository
git clone [https://github.com/YOUR_USERNAME/gandalf-game.git](https://github.com/YOUR_USERNAME/gandalf-game.git)
cd gandalf-game

# Install dependencies
go mod tidy