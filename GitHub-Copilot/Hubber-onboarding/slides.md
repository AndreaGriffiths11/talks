---
theme: default
image: https://github.com/user-attachments/assets/991ef25b-7444-4f0b-bb9b-5401e2765611

title: A Brief Introduction to GitHub Copilot
favicon: ''
font:
layout: image
lineNumbers: true
transition: fade
record: dev
download: true
exportFilename: hubber-orientation-copilot-101
export:
  format: pdf
  timeout: 30000
  dark: false
  withClicks: false
---

---
layout: image-right
image: https://github.com/user-attachments/assets/f3136c19-ec37-41a2-b101-eb6aaf5592f9
transition: fade-out
---

# Hi! I'm Andrea!

- Mami to 👦🏼👦🏻 + 🐶🐶 + 🐟
- Wife to a 🏴󠁧󠁢󠁷󠁬󠁳󠁿 👨🏼‍🦱
- 👩🏽‍💻Sr. Developer Advocate at GitHub
- 🇺🇸 Army Veteran
- 🇨🇴 Immigrant 
- 🦸‍♀️ OSS superfan 
- 🎀 Breast cancer slayer 

<br><br><br><br><br>

**Find me online @alacolombiadev**

<style>
h1 {
  background-color: #E81CFF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: intro
transition: fade-out
---

# What we'll cover:

- What is GitHub Copilot?
- Features of GitHub Copilot
- How does it work?
- Access & Installation
- Demos
- Q&A

<style>
h1 {
  background-color: #E81CFF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# What is GitHub Copilot?

An AI pair programmer that helps developers write code faster
- The world's most widely adopted AI developer tool
- Your intelligent coding companion that understands context
<br> 

<img src="https://github.com/LadyKerr/mealmetrics-copilot/assets/47188731/b3b0193f-913f-49b3-860e-9659db72a348" alt="GitHub Copilot" width="100%"/>

<style>
h1 {
  background-color: #40C9FF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# What is GitHub Copilot?

### You can use GitHub Copilot in your IDE. 
### It is available in VSCode, Neovim, Jetbrain IDE and Visual Studio.

<br>

![various-ide-copilot](https://github.com/user-attachments/assets/67a8cae5-a9cd-4690-b751-96c6ac852920)

![lprogramming-langauges](https://github.com/LadyKerr/mealmetrics-copilot/assets/47188731/94e3f958-bb51-4b47-b698-f6da3a992483)

<style>
h1 {
  background-color: #40C9FF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# What is GitHub Copilot?

### You can use GitHub Copilot on GitHub dotcom. 
### talk to your repos, create docs, draft PRs, inquire about issues and more.

<br>

![copilot-chat-dotcom](https://github.com/user-attachments/assets/8761ef7f-4329-4036-b263-621633e4204a)

<style>
h1 {
  background-color: #40C9FF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# Features of GitHub Copilot

- Code Complete (inline suggestions)
- Copilot Chat (inline and chat box)
- Copilot Chat on Mobile!
- Copilot in the CLI
- Copilot PR Summaries (ent)
- Copilot Knowledge bases (ent)
- Copilot Extensions (Public beta)
- Copilot Autofix for CodeQL

![subscribe-rss-feed-copilot](https://github.com/user-attachments/assets/d8a59971-e365-435e-824d-bfbfe21afd9f)

<style>
h1 {
  background-color: #E81CFF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# What is GitHub Copilot good for?

- 🛠️ Generating boilerplate code and working with frameworks
- 🤷🏽‍♀️ Helping with uncommon or confusing syntax
- 🔗 Pattern matching
- 👨🏽‍💻 Code translation
- ⛓️ Creating Cron jobs and regex
- 👀 Helping you remember things you forgot
- 💻 Extending and refactoring existing code
- 🔖 Explaining unfamiliar code
- 📝 Writing Documentation (which we all love to write!)
- 🚨 Understanding error messages (and helping you fix it!)
- 🧪 Writing unit tests

. . . and much more! 🚀

<style>
h1 {
  background-color: #40C9FF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
transition: fade-out
---

# How does it work?

<style>
h1 {
  background-color: #40C9FF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
layout: center
---

![copilot-flow](https://github.com/user-attachments/assets/04481664-4c88-4f39-b5a5-c0312d38104a)

---
transition: fade-out
layout: center
---

![sources](https://github.com/user-attachments/assets/a54258a4-5d7f-4456-9548-1979e4e1e9a9)

---
transition: fade-out
layout: center
---

![life-of-a-completion](https://github.com/user-attachments/assets/b4184921-7699-45ca-bed9-9f7244f98aaa)

---
transition: fade-out
---

# Some Limitations of GitHub Copilot 

- GitHub copilot != Compiler
- The AI cannot read your mind 
- The AI is not a replacement for good coding practices

<style>
h1 {
  background-color: #40C9FF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# Best Practices for Using GitHub Copilot

- 👀 Review all generated code carefully
- 🧩 Break down complex tasks into smaller chunks
- 📝 Write clear comments and provide good context
- 💬 Use Copilot Chat when you need explanations
- 🔨 Combine Copilot with your expertise
- 🚀 Start simple and gradually explore advanced features

<style>
h1 {
  background-color: #E81CFF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
layout: center
---

# DEMO

<style>
h1 {
  background-color: #40C9FF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
layout: center
---

# More resources..

<style>
h1 {
  background-color: #40C9FF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# Resources

- [Coding with an AI Pair Programmer](https://youtu.be/dhfTaSGYQ4o?si=wdhu3C7uwG5cqX0K)
- [What's new with GitHub Copilot from VsCode team](https://twitter.com/code/status/1737903911237718467)
- [How to use GitHub Copilot: Prompts, tips, and use cases](https://github.blog/2023-06-20-how-to-write-better-prompts-for-github-copilot/)
- [Prompting GitHub Copilot Chat to become your personal AI assistant for accessibility](https://github.blog/2023-10-09-prompting-github-copilot-chat-to-become-your-personal-ai-assistant-for-accessibility/)
- [How to build a GPT-3 App with Nextjs, React, and GitHub Copilot](https://github.blog/2023-07-25-how-to-build-a-gpt-3-app-with-nextjs-react-and-github-copilot/)
- [Demo repo - MealMetrics](https://github.com/LadyKerr/mealmetrics-copilot)
- [Code Smarter not Harder slides and repo](https://github.com/LadyKerr/gh-copilot-talk)
- [Click here to connect with Andrea](https://www.linkedin.com/in/alacolombiadev)

<style>
h1 {
  background-color: #40C9FF;
  background-image: linear-gradient(45deg, #40C9FF 10%, #E81CFF 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>
