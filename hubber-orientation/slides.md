---
theme: seriph
title: A Brief Introduction to GitHub Copilot
favicon: ''
font: Playfair Display
layout: cover
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

<!--
Hello good morning! Thank you all for being here with me today! I hope you've been enjoyng orientation, welcome to GitHub!
-->

## GitHub Copilot 101

A brief introduction for Hubbers in every department, presented by @francisfuzz

---
layout: image-right
image: https://avatars.githubusercontent.com/u/15894826?v=4
transition: fade-out
---

# 👋 I'm @francisfuzz!

- Pronouns: he/him
- Husband and Father 💍 👶
- Pilipino descent, based in Southern California 🏄‍♂️
- Senior Software Engineer, New User Experience team 🍄
- Committed to completing an Ironman 70.3 in December 2024 💪

<br>

Thanks for having me! I'm here to help you make the most of GitHub Copilot as a Hubber.

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
Hello! I'm Francis! I go by francisfuzz on the Interwebs.

I'm a software engineer at GitHub working on the NUX team. NUX stands for New User Experience.

I invite you to learn more about GitHub Copilot and how you can make the most out of this tool.
-->

---
layout: intro
transition: fade-out
---

# Where we're going: 

## [time in minutes] topic

- [4] What is GitHub Copilot?
- [4] Copilot Features
- [4] Access & Installation
- [10] Live Demo(s)
- [5] Recap
- [35] Q&A

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
We'll take a brief look at what GitHub Copilot is, what it's good for, how it works, tips to get the most out of it, and then we'll do some live demos.
-->

---
transition: fade-out
---

# What is GitHub Copilot? (1/3)

### GitHub Copilot is an AI pair programmer that helps you write code faster.

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

Just in case you didn't know, GitHub Copilot is an AI pair programmer that helps you write code faster. 

It is designed to help with programming tasks and serves as your assistant while you're working in your IDE. 

It is The world’s most widely adopted AI developer tool.

-->

---
transition: fade-out
---

# What is GitHub Copilot? (2/3)

### You can use GitHub Copilot in your IDE. 
### It is available in VSCode, Neovim, Jetbrain IDE and Visual Studio.

<br>

![various-ide-copilot](https://github.com/LadyKerr/mealmetrics-copilot/assets/47188731/e39af215-9314-4524-8c23-eb3e0b280308)

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
To install it you'll go to your respective marketplaces for your IDE and install the extension.

Once it's installed you'll need to authenticate with your GitHub account. 

When you have accesss, you'll be able to use GitHub Copilot in your IDE.

And it works with many languages, like javascript, typescript, python, java, python, go, ruby, and more.
-->


---
transition: fade-out
---

# What is GitHub Copilot? (3/3)

### You can use GitHub Copilot on GitHub dotcom. 
### talk to your repos, create docs, draft PRs, inquire about issues and more.

<br>

![copilot-chat-dotcom](https://github.com/user-attachments/assets/2268dc33-8205-4e83-902e-7abf45449b12)


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
You can use GitHub Copilot on GitHub dotcom. 

There's a lot that you can do:
- ask it about your repositories like explaining a piece of code
- create documentation
- draft pull requests
- inquire about issues
-->

---
transition: fade-out
---

# Copilot Features

- Code Complete (inline suggestions)
- Copilot Chat (inline and chat box)
- Copilot Chat on GitHub Mobile (iOS and Android)
- Copilot in the CLI: https://cli.github.com
- Enterprise: Copilot PR Summaries & Copilot Knowledge bases (Enterprise)
- Copilot Extensions (Public beta)
- Copilot Autofix for CodeQL

Keep up with the latest: https://github.blog/ai-and-ml/github-copilot/

![copilot-chat-dotcom](https://github.com/user-attachments/assets/d8a59971-e365-435e-824d-bfbfe21afd9f)

<!--
GitHub Copilot is comprised of a suite of products that goes beyond code completion.

You could think about GitHub Copilot not just a single product, but as a platform of products.

Some of the tools that accompany GitHub Copilot includes a chat interface that you can use in your IDE, a command line tool via a GitHub CLI extension, GitHub Copilot for PRs, Copilot integrated into dotcom and many more. Today, we'll be looking at a few of the features that I've found to be most useful during my everyday development.

FRANCIS MUST PROVIDE EXAMPLES FROM AT LEAST 2-3 BULLETS ON THIS SLIDE IN REAL LIFE

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


---
transition: fade-out
---

# What is GitHub Copilot good for? (1/2)

For developers:

- 🛠️ Boilerplate code and frameworks
- 🤷🏽‍♀️ Uncommon or confusing syntax
- 🔗 Pattern matching
- 👨🏽‍💻 Translate Code
- ⛓️ Cron jobs and regex
- 👀 Helping you remember things you forgot
- 💻 Extending and refactoring existing code
- 🔖 Explaining unfamiliar code
- 📝 Documentation (which we all love to write!)
- 🚨 Understandiing error messages (and fixing it!)
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

Many things! Some of what it's best at is . . .
-->

---
transition: fade-out
---

# What is GitHub Copilot good for? (2/2)

Even if you're not a developer...

For product managers:

- 📊 Analyzing data and generating reports
- 📝 Drafting product specifications and documentation

For designers:

- 🎨 Generating code snippets for design prototypes
- 🖌️ Generating CSS styles to match a particular design system

For any writing-related task (every Hubber):

- ✏️  Drafting personalized communications for your audience
- 🦅 Proofreading and generating alternative phrasing
- 😌 Translating technical jargon into accessible language

---
transition: fade-out
---

# Some Limitations of GitHub Copilot 

- GitHub Copilot != Compiler
- The AI cannot read your mind (here's where Francis tells a story)
- The AI is not a replacement for secure, correct coding practices, as well as your unique expertise and skills

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
It is also not here to replace your expertise and skills. Remember that you are in charge, and Copilot is a powerful tool at your service.

-->

---
layout: center
transition: fade-out
---

# Time for demos

- Demo P: validating an email address
- Demo Q: generating great questions

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

<!---

SLIDES: https://github.com/LadyKerr/gh-copilot-talk/blob/main/hubber-orientation/hubber-orientation-copilot-101.pdf

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
---

# Resources

- [Coding with an AI Pair Programmer](https://youtu.be/dhfTaSGYQ4o?si=wdhu3C7uwG5cqX0K)
- [What's new with GitHub Copilot from VsCode team](https://twitter.com/code/status/1737903911237718467)
- [How to use GitHub Copilot: Prompts, tips, and use cases](https://github.blog/2023-06-20-how-to-write-better-prompts-for-github-copilot/)
- [Prompting GitHub Copilot Chat to become your personal AI assistant for accessibility](https://github.blog/2023-10-09-prompting-github-copilot-chat-to-become-your-personal-ai-assistant-for-accessibility/)
- [How to build a GPT-3 App with Nextjs, React, and GitHub Copilot](https://github.blog/2023-07-25-how-to-build-a-gpt-3-app-with-nextjs-react-and-github-copilot/)
- [Demo repo - MealMetrics](https://github.com/LadyKerr/mealmetrics-copilot)
- [Code Smarter not Harder slides and repo](https://github.com/LadyKerr/gh-copilot-talk)

<br>
<br>

Francis Batac | @francisfuzz | Senior Software Engineer @GitHub

🫧 ✨ Thank you! ✨ 🫧

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

# Questions & Answers

The floors is yours! 🎤

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