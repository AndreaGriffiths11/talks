---
theme: seriph
image: https://github.com/user-attachments/assets/991ef25b-7444-4f0b-bb9b-5401e2765611
title: A Brief Introduction to GitHub Copilot
favicon: ''
camera: true
font:
environment: both
layout: image
lineNumbers: true
presenter: true
transition: fade
record: true
download: true
exportFilename: hubber-orientation-copilot-101
export:
  format: pdf
  timeout: 30000
  dark: false
  withClicks: false
---

<!--
Welcome to our introduction to GitHub Copilot, or as I like to call it - Meet Your New BFF! I'm excited to show you how this tool will transform your work at GitHub.
-->

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

<!--
Hi everyone! I'm Andrea! Before we dive in, let me share a bit about myself. I'm a mom to two wonderful boys, two dogs, and a fish. I'm married to a wonderful Welshman, and I'm a Senior Developer Advocate here at GitHub. I'm also proud to be a US Army veteran, a Colombian immigrant, an open source superfan, and a breast cancer survivor. You can find me online @alacolombiadev.  My journey to tech has been anything but traditional. I've worn many hats at GitHub - from nurturing our Open Source community, to supporting developers, to @GitHub Help support, later PMing, and now as a developer advocate. This diverse background has given me a unique perspective on how AI tools can benefit everyone, not just developers.
-->

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

<!--
Today we'll walk through:
What GitHub Copilot is
Its key features
How it works behind the scenes
How to get access and install it
Live demos
And plenty of time for Q&A
Here's what fascinates me about Copilot: while it's made headlines as an AI coding assistant, what many don't realize is that it's revolutionizing how we work with all kinds of content. Whether you're writing documentation, crafting user stories, or managing projects, Copilot has surprising capabilities that can make your work more efficient and creative. Today, I'll show you how Copilot can be your ally, regardless of your role or technical background. And I promise you'll leave with practical tips you can start using immediately.
-->

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

<!--

But first, what is GitHub Copilot? :thinking:

Just in case you didn't know, GitHub Copilot is an AI pair programmer that helps you write code faster. It is designed to help with programming tasks and serves as your assistant while you're working in your IDE. It is The world’s most widely adopted AI developer tool.

-->

---
transition: fade-out
---

# Installation and Availability

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

<!--
To install it you'll go to your respective marketplaces for your IDE and install the extension. Once it's installed you'll need to authenticate with your GitHub account. and if you have accesss, you'll be able to use GitHub Copilot in your IDE. Is available free for in VS Code, visual studio and neovim. Lucky you you work here so you have a full pro license!
GitHub
V S code
Visual Studio
Xcode
JEtbrains IDE
NeoVim
Azure Data Studio
And it works with many languages - especially open source languages like javascript, typescript, python, java, python, go, ruby, and more.
-->

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

<!--
Beyond IDEs, Copilot is integrated right into GitHub.com. You can use it to talk to your repositories, create documentation, draft pull requests, and get insights about issues
-->

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

<!--
GitHub Copilot is comprised of a suite of products that goes beyond code completion.

Some of the tools that accompany GitHub Copilot includes a chat interface that you can use in your IDE, a command line tool via a GitHub CLI extension, GitHub Copilot for PRs, Copilot integrated into dotcom and many more. Today, we'll be looking at a few of the features that I've found to be most useful during my everyday development.


-->

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

<!--
Copilot comes with a powerful suite of features:

Code completion with inline suggestions
Copilot Chat for conversations about your code
Mobile accessl, if you ahvent download the mobile app
CLI integration
PR summaries for enterprise users
Knowledge bases
Extensions in public beta
And automated fixes for CodeQL
-->

---
transition: fade-out
---

# What is GitHub Copilot good for?

- 🛠️ Generating boilerplate code and working with frameworks
- 🤷🏽‍♀️ Helping with uncommon or confusing syntax
- 🔗 Pattern matching
- 👨🏽‍💻 Code translation
- ⛓️ Creasting Cron jobs and regex
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

<!--
Now what is GitHub Copilot good for?

Many things! Some of what it's best at is . . .Copilot excels at many tasks:

Generating boilerplate code
Helping with tricky syntax
Pattern matching
Code translation
Creating cron jobs and regex
Remembering things you might forget
Refactoring code
Explaining unfamiliar code
Writing documentation (yes, even the parts we don't love!)
Understanding error messages
Writing unit tests
And that's just the beginning!"
-->

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

<!--
Let me walk you through how Copilot works behind the scenes.
-->

---
transition: fade-out
layout: center
---

![copilot-flow](https://github.com/user-attachments/assets/04481664-4c88-4f39-b5a5-c0312d38104a)
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

<!--
It starts with the OpenAI Codex model, integrates with GitHub's vast code repository, and provides context-aware suggestions right in your editor
-->

---
transition: fade-out
layout: center
---

![sources](https://github.com/user-attachments/assets/a54258a4-5d7f-4456-9548-1979e4e1e9a9)


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

<!--
Open Tabs
First, Copilot is aware of all the tabs you have open in your editor. This provides crucial context about the broader project you're working on.
Data from Editor
Second, it's collecting real-time information about what you're currently typing and where your cursor is located.
Semantic Data
Third, it's analyzing the semantic meaning of your code - not just the syntax, but what your code is trying to accomplish.

These three sources combine to provide context to GitHub Copilot,  to generate relevant code suggestions. The system processes these inputs through a prompt library and contextual filter model before generating completions.
-->

---
transition: fade-out
layout: center
---

![life-of-a-completion](https://github.com/user-attachments/assets/b4184921-7699-45ca-bed9-9f7244f98aaa)

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

<!--
behind the scenes.
It returns suggestions to your editor where you choose what to accept or ignore.
KEY REMEMBER it will no act agentically for you.

GitHub Copilot shares data in an ephemeral way. It’s shared just long enough for GitHub Copilot to provide a suggestion. We do not take that code and put it back into the data model for suggestions.

All of this information flows into what we call the Prompt Library
The Prompt Library
Think of the Prompt Library as a smart organizer. It:

Takes all this local context
Prioritizes what's most relevant
Structures it in a way the AI can understand
Creates a formatted prompt

We're constantly improving how this library works to provide better context from all available sources

The Prompt
"The prompt is fascinating because it contains:

Text before your cursor (the prefix)
Text after your cursor (the suffix)
Relevant context from your coding session

This 'Fill-in-the-Middle' approach is what makes Copilot so effective at understanding your intent."
Server-Side Processing
"Once the prompt is ready, it moves to GitHub's servers where three crucial steps happen:
Contextual Filter Model
"First, a filter examines the prompt and session context to decide if:

- The request is appropriate
- The context is sufficient
- A suggestion would be helpful
This is like a quality control checkpoint before involving the main AI model.

GPT Model
"If approved, the prompt goes to the GPT model, which:

Analyzes the context
Understands the programming patterns
Generates multiple possible completions
We're continuously working on improving these model engines specifically for Copilot.

Completion Generation
"The model generates 'n' completions - multiple suggestions that could work in your context. These are then filtered one final time before being shown to you."
Final Output
"The last step is showing you '≤n completions' - meaning you might see one or several suggestions, but always the best ones the system generated."
Continuous Improvement
"What makes this system particularly powerful is that it's constantly evolving:

The local components are getting better at providing context
The server components are being optimized for better suggestions
The entire pipeline is being refined for speed and accuracy

Understanding this lifecycle helps you work more effectively with Copilot. When you know how it processes context and generates suggestions, you can better structure your code and prompts to get the most helpful completions.
-->

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

<!--
It cannot read minds, although it sometimes feels like it can. It’s not a compiler, and it’s not a replacement for good coding practices. Actually if you have bad coding practices this will be more apparent when you use the AI because it uses the patterns in your code to give you suggestions.

This means, if you have bad coding practices, you’ll get bad suggestions. So it’s important to keep that in mind when you’re using it.

Also, one of the most important points I want to drive home today is that - GitHub Copilot is a tool that can help you write code faster, and it’s up to you to decide how to use it. 

It is not here to do your work for you or to write everything for you. It will guide you and nudge you in the right direction just as a coworker would if you asked them questions or for guidance on a particular issue.

Copilot is not designed to espond to prompts unrelated to coding and technology
It is also not here to replace your expertise and skills. Remember that you are in charge, and Copilot is a powerful tool at your service.# Best Practices for Effective Use of GitHub Copilot

Think of GitHub Copilot like a skilled apprentice working alongside you - eager to help but needing proper guidance to be most effective.

* 👀 **Quality Control Matters**: Always review generated code carefully. Like any collaborative work, verification is key to maintaining quality and security.

* 🧩 **Divide and Conquer**: Complex problems become manageable when broken down. Feed Copilot smaller, well-defined tasks rather than massive, ambiguous ones.

* 📝 **Clear Communication**: The better your comments and context, the more relevant Copilot's suggestions. Good input leads to good output.

* 💬 **Leverage the Dialog**: Use Copilot Chat when you need deeper understanding. It's like having a senior developer available for quick consultations.

* 🔨 **Combine Forces**: Let Copilot enhance your expertise, not replace it. Your knowledge and judgment remain essential.

* 🚀 **Progressive Learning**: Start with basic features and gradually explore more advanced capabilities as you become comfortable.

Remember: Copilot adapts to your coding patterns - both good and bad. If you write unclear or inefficient code, Copilot will learn and suggest similar patterns. Think of it as a mirror reflecting your own coding practices.

Copilot is designed to augment your development process, not take it over. It's a sophisticated tool that works best when guided by your expertise and judgment. Like any good assistant, it helps you work more efficiently while leaving the important decisions in your hands.

The key is understanding that Copilot is part of your development toolkit - a powerful one, but still just a tool. You're the developer, the decision-maker, and the one responsible for the final code. Use Copilot to enhance your capabilities, not replace your critical thinking.  # Best Practices for Effective Use of GitHub Copilot
-->

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
<!--




-->
<!--
-

General demo:

## Installation
- open vscode and search for extension, install then auth
- click "your copilot" and show settings page
- back to editor, click on copilot icon at the bottom, show panel
- click chat icon in panel 

## IDE Demo
- code complete: validate email address
start typing to show code complete in action

```
import re

emailToVerify = 'hello@email.com'
match = re.match(r'[^@]+@[^@]+\.[^@]+', addressToVerify)

if match == None:
    print('Bad Syntax')
    raise ValueError('Bad Syntax')

```

- use `/explain` to explain the code
- ask copilot: 
```
Create an impressive creative coding demo in python for 8,000 engineers at the developer week conference. This must be splashy and very very impressive to make people want to use GitHub Copilot. Can you help me and make something please?
```
- save code in a new file
- run with python <filename> (get an intentional error)
- error message in terminal, highlight and have copilot explain
- resolve error
- run again (wow)

- ask copilot: 

```
what else can I add to the game?
```

- implement suggestions
- ask: can I create wave sounds and save it as particle.wav?

- show slash commands, agents,
- /test . . . and all
- @github what can you do? how can I use git?
- #file:game.py generate a readme file for this game


## DOTCOM - Chat is Ent only currently
**On devrel repo**
- ask copilot: what are the most recent issues assigned to me?
- ask copilot: summarize this issue
- ask copilot: how do I create a markdown table?
- ask: where can I find the file about video editing?

- Push code and generate a summary
- highlight code and ask for explanations/help
- go to repo, highlight function, ask for help: https://github.com/LadyKerr/noseknows-demo
-->

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
- [Profiles app to play!](https://github.com/AndreaGriffiths11/profiles/settings)


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
