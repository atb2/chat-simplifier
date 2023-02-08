# [Chat Simplifier](https://chat-simplifier.vercel.app/)
[![](https://img.shields.io/badge/chat-on%20discord-7289da.svg?sanitize=true)](https://chat.imzbb.cc)

This project simplify chat content for you using AI.

[![Chat Simplifier](./public/screenshot.png)](https://chat-simplifier.vercel.app/)

## How it works

This project uses the [OpenAI GPT-3 API](https://openai.com/api/) (specifically, text-davinci-003) and [Vercel Edge functions](https://vercel.com/features/edge-functions) with streaming. It constructs a prompt based on the form and user input, sends it to the GPT-3 API via a Vercel Edge function, then streams the response back to the application.

## Running Locally

After cloning the repo, go to [OpenAI](https://beta.openai.com/account/api-keys) to make an account and put your API key in a file called `.env`.

Then, run the application in the command line and it will be available at `http://localhost:3000`.

```bash
npm run dev
```

## Credits

Inspired by [TwtterBio](https://github.com/Nutlope/twitterbio) and [Jimmy Lv](https://www.bilibili.com/video/BV17M411i7B6).

## 支持

如果你觉得这个工具对您有帮助，可以帮作者买一杯果汁 🍹 表示支持

![](https://imzbb.cc/img/sponsorship.png)
