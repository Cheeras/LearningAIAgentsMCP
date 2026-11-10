Learning AI Agents


## Agenda:

- What is AI Agent ?
- What is the MCP and how LLM connects to MCP to become more powerful
- AI Agent that perform web browser Testing using Selenium, Playwright
- Task 1 - Basic Task
- Task 2 - Medium Task
- Task 3 - Advance stuff
- Github MCP Server - Push code via Prompts(Like 5th Grade)

AI Agent = LLM + Memory + Tools

===================================

What is AI Agent ?

Autonomous Task Performer - An AI agent is a system that can perceive its environment. make decisions and take actions to achieve specific goals with out needing constant human input

Goal-Oriented & Adaptive - It's designed to learn, adapt and optimize its behavior based on feedback, data or changing conditions( ex: a chatbot answering questions, or an automation bot handling workflows)

Powered by AI Models - AI agents usually combines machine learning, natural language processing, and reasoning to understand context, plan steps and execute tasks - often integrating with tools, APIs, or other systems

## What is an AI Agent?

"An AI Agent is an intelligent system powered by an LLM that uses memory and external tools to understand goals, make decisions, perform actions, and achieve tasks autonomously."

1. Autonomous Task Performer

An AI Agent is a smart software program that can understand a task, make decisions, and perform actions to achieve a specific goal without needing constant human instructions.

2. Goal-Oriented and Adaptive

An AI Agent works towards achieving a specific goal. It can learn from feedback, adjust its approach, and improve its actions based on new information or changing situations.

3. Powered by AI Models

An AI Agent uses AI models (LLMs) as its brain to understand instructions, analyze information, make decisions, and plan the next steps. It can also connect with external tools, APIs, and applications to perform tasks automatically.

In simple words: An AI Agent is like a digital assistant. You give it a goal, and it figures out the steps and uses the required tools to complete the task.

![image.png](https://eraser.imgix.net/workspaces/IudpwZWh3cgqEsEgP0VQ/XSQENpYGquT8jEr2XHnLoL3QdCM2/image_K6QqyZEo6ekbpNXJiUxtr.png?ixlib=js-3.8.0 "image.png")

What is the MCP and How this MCP help an LLM to be superman.

How application provide the context to LLM

now for example if you ask LLM Python Webinar of the AI knowledge sharing session

MCP(Model Context Protocal) is an open-source standard for connecting AI Applications to external systems.

source: - [anthropic.skilljar.com/introduction-to-model-context-protocol](https://anthropic.skilljar.com/introduction-to-model-context-protocol)

![image.png](https://eraser.imgix.net/workspaces/IudpwZWh3cgqEsEgP0VQ/XSQENpYGquT8jEr2XHnLoL3QdCM2/image_HcC2rbT1HkfGeR-7RzYPM.png?ixlib=js-3.8.0 "image.png")

MCP servers list:

[github.com/punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)

---

Task 1 - MCP (Web Testing MCPs)

We need to install

1. Cursor AI
2. Install the MCP Server
3. Chat and Give Prompt

---

Most of the MCP servers requires node js

install the Node js

[nodejs.org/en/download](https://nodejs.org/en/download)

can you open the [app.vwo.com](https://app.vwo.com/) and add the random email,password in the text box and click on the submit button and verify error message after some time using the playwright mcp and close the browser at the end

See this observer this care full here

By using this prompt LLM called and connecting to Playwright MCP servers connect to perform the task and start the calling the functions which are written where are these functions
