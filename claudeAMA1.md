# Claude AMA1

## Q1. What is RAG?
**Answer:** RAG (Retrieval-Augmented Generation) lets Claude search documents or a knowledge base before answering. This helps it give more accurate and updated answers.

## Q2. What are the components of the MCP model?
**Answer:** The main components are the **Host**, **Client**, and **Server**. The Host runs the AI, the Client connects to servers, and the Server provides tools or data.

## Q3. What are the different models in the Claude family?
**Answer:** The Claude family has **Haiku**, **Sonnet**, **Opus**, and **Fable**. Haiku is the fastest, Sonnet is best for most tasks, Opus is for difficult tasks, and Fable is the most powerful.

## Q4. What is the purpose of using Plan Mode?
**Answer:** Plan Mode helps Claude think before doing a task. It breaks a big task into small steps and creates a clear plan.

## Q5. What is MCP?
**Answer:** MCP (Model Context Protocol) is a standard way for AI models to connect with tools, files, databases, and other applications.

## Q6. What are the different MCP transports?
**Answer:** MCP supports **STDIO**, **HTTP**, and **Streamable HTTP (SSE)**. These are different ways for the client and server to communicate.

## Q7. What is a subagent?
**Answer:** A subagent is a helper AI that handles one specific task. It finishes the task and sends the result back to the main agent.

## Q8. What is the difference between `CLAUDE.md` and Rules files?
**Answer:** `CLAUDE.md` stores instructions for a specific project. Rules files contain general instructions that Claude follows while working.

## Q9. Why should we use MCP servers?
**Answer:** MCP servers let Claude use external tools, read files, access databases, and perform actions. This makes Claude more useful than using only its built-in knowledge. Eg: Github.
